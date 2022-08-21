<template>
  <main>
    <nav-bar current-page="Components" />
    <div class="max-w-screen-lg mx-auto">
      <div class="bg-card-light dark:bg-card-dark m-6 p-6 shadow-md dark:shadow-shadow-dark hover:shadow-none hover:rounded motion-safe:animate-fade-in-fast transition">
        <p class="text-center text-3xl font-bold">Components</p>
      </div>
      <divider />

      <div v-if="components && components.length">
        <tag-group-preview
          v-for="(component, i) in components"
          :key="component.slug"
          :tag-group="'components'"
          :tag="component"
          :index="i"
        />
      </div>

      <div v-else-if="!isDoneFetchingComponents">
        <tag-group-preview
          v-for="(n, i) in 3"
          :key="`tag-lazy-loader-${n}`"
          :index="i"
        />
      </div>
      
      <div v-else class="bg-card-light dark:bg-card-dark m-6 p-6 hover:rounded shadow-md dark:shadow-shadow-dark hover:shadow-none motion-safe:animate-fade-in transition col-span-2">
        <p class="text-center md:text-left text-2xl font-bold mt-2">No tags 😴</p>
        <p class="text-center md:text-left">There are not currently any tags</p>
      </div>

    </div>
    <back-to-top-button />
    <footer-bar current-page="Components" />
  </main>
</template>

<script>
import Divider from '@/components/Divider.vue';
import TagGroupPreview from '@/components/previews/TagGroup.vue';
import NavBar from '@/components/NavBar.vue';
import FooterBar from '@/components/FooterBar.vue';
import BackToTopButton from '@/components/BackToTopButton.vue';

export default {
  name: 'components',
  components: {
    TagGroupPreview,
    Divider,
    NavBar,
    BackToTopButton,
    FooterBar
  },
  async asyncData({ $content, error }) {
    const content = await $content('tags/components/components')
      .fetch()
      .catch((err) => {
        error({
          statusCode: 500,
          message: 'Something went wrong while fetching tags',
          error: err
        });
      });

    return {
      components: content.tags,
      isDoneFetchingComponents: true
    };
  },
};
</script>
