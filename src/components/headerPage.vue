<template>
  <header>
    <div class="container-header">
      <img src="img/dc-logo.png" alt="dc-logo">
      <ul class="header-text">
        <li><a href="!">CARACTERS</a></li>
        <li><a href="!">COMICS</a></li>
        <li><a href="!">MOVIES</a></li>
        <li><a href="!">TV</a></li>
        <li><a href="!">GAMES</a></li>
        <li><a href="!">COLLECTIBLES</a></li>
        <li><a href="!">VIDEOS</a></li>
        <li><a href="!">FANS</a></li>
        <li><a href="!">NEWS</a></li>
        <li><a href="!">SHOP</a></li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: 'headerPage',
};
</script>

<style lang="scss" scoped>
  .container-header{
    font-family: 'Roboto', sans-serif;
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 70px;

    ul {
      display: flex;
      justify-content: space-around;
      align-items: center;
      list-style: none;
      gap: 1rem;
      height: 100%;

      li{
        height: 100%;
        a{
        text-decoration: none;
        color: black;
        border-bottom: 3px solid white;
        height: 100%;
        display: flex;
        align-items: center;

        &:hover{
          color: #0282F9;
          border-color: #0282F9;
        }
      }
      }
    }
  };
</style>
