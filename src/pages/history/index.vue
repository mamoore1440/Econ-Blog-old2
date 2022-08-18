<template>
  <main>
    <nav-bar current-page="Home" />
    <p>TODO I guess. Literally this will be made in >1 year</p>
    <footer-bar current-page="Home" />
  </main>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
import FooterBar from '@/components/FooterBar.vue';

export default {
  name: 'history',
  components: {
    NavBar,
    FooterBar,
  }
};
</script>
