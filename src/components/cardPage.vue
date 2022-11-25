<template>
  <div class="card">
    <img
      :src="imgUrl"
      alt="fumetto"
    >
    <h3>{{ title }}</h3>
  </div>
</template>

<script>
export default {
  name: 'CardPage',
  props: {
    imgUrl: String,
    title: String,
  },
};
</script>

<style lang="scss" scoped>
  .card{
    text-align: center;
  }
</style>
