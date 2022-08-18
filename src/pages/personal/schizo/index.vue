<template> 
  <main>
    <nav-bar current-page="Schizo" />
    <blog-feed route='/personal/schizo'/>
    <back-to-top-button />
    <footer-bar current-page="Schizo" />
  </main>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
import BlogFeed from '@/components/BlogFeed.vue';
import FooterBar from '@/components/FooterBar.vue';
import BackToTopButton from '@/components/BackToTopButton.vue';

export default {
  name: 'schizo',
  components: {
    NavBar,
    BlogFeed,
    BackToTopButton,
    FooterBar
  },
};
</script>
<!-- Copy of blog.vue -->
