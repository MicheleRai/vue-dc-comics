<template>
  <div class="container-main">
    <div class="content-main">
      <h1> --> Content goes here &lt;-- </h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'mainPage',
};
</script>

<style lang="scss" scoped>
  .container-main{
    font-family: 'Roboto', sans-serif;
    background-color: #1C1C1C;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 200px;
    .content-main{
      max-width: 1200px;
      margin: auto
    }
  };
</style>
