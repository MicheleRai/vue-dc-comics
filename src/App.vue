<template>
  <body>
    <headerPage />
    <mainPage />
    <iconPage />
    <footerPage />
  </body>
</template>

<script>
import headerPage from '@/components/headerPage.vue';
import mainPage from '@/components/mainPage.vue';
import iconPage from '@/components/iconPage.vue';
import footerPage from '@/components/footerPage.vue';

export default {
  components: {
    headerPage,
    mainPage,
    iconPage,
    footerPage,
  },
};
</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap');
   * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>
