<template>
  <div id="nav-bar" class="bg-menu-light dark:bg-menu-dark transition">
    <nav class="mx-auto max-w-6xl flex items-center justify-between flex-wrap p-4 py-6 px-5">
      <nav-item
        :href="signatureHeader.href"
        :active="currentPage === 'Home'"
        class="font-bold">
        {{ signatureHeader.title }}
      </nav-item>
        
      <div class="justify-between">
        <nav-item
          v-for="item in items"
          :key="item.title"
          :href="item.href"
          :active="currentPage === item.title"
        >
          {{ item.title }}
        </nav-item>
        <tag-dropdown :current-page="currentPage" :tag-group="'components'"/>
        <tag-dropdown :current-page="currentPage" :tag-group="'fundamentals'"/>
        <tag-dropdown :current-page="currentPage" :tag-group="'markets'"/>
        <tag-dropdown :current-page="currentPage" :tag-group="'specials'"/>
      </div>
    </nav>
  </div>
</template>

<script>
import TagDropdown from './TagDropdown.vue';
import NavItem from './NavItem.vue';

export default {
  name: 'nav-bar',
  components: {
    TagDropdown,
    NavItem
  },
  props: {
    currentPage: {
      type: String,
      default: ''
    }
  },
  data: () => ({
    signatureHeader: {
      title: process.env.NUXT_ENV_FULL_NAME,
      href: '/'
    },
    items: [
      {
        title: 'Trading',
        href: '/personal/trading'
      },
      {
        title: 'Thesis',
        href: '/personal/thesis'
      },
      {
        title: 'Blog',
        href: '/personal/blog'
      },
      {
        title: 'Schizo',
        href: '/personal/schizo'
      }
    ],
  })
};
</script>
