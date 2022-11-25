<template>
  <a
    class="card"
    href="!"
  >
    <img
      :src="imageUrl"
      alt="fumetto"
    >
    <h3>{{ title }}</h3>
  </a>
</template>

<script>
export default {
  name: 'CardPage',
  props: {
    imageUrl: {
      type: String,
      default: String,
    },
    title: {
      type: String,
      default: String,
    },
  },
};
</script>

<style lang="scss" scoped>
  .card{
    text-align: center;
    text-decoration: none;
    color: white;

    &:hover{
      background: white;
      color: #0282F9;
    }
  }
</style>
