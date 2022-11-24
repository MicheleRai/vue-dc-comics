<template>
  <div class="container-icon">
    <ul>
      <li><a href="!"><img src="img/buy-comics-digital-comics.png" alt="1"> DIGITAL COMICS</a></li>
      <li><a href="!"><img src="img/buy-comics-merchandise.png" alt="1"> DC MERCHANDISE</a></li>
      <li><a href="!"><img src="img/buy-comics-subscriptions.png" alt="1"> SUBSCRIPTION</a></li>
      <li><a href="!"><img src="img/buy-comics-shop-locator.png" alt=""> COMIC SHOP LOCATOR</a></li>
      <li><a href="!"><img src="img/buy-dc-power-visa.svg" alt="1"> DC POWER VISA</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'iconPage',
};
</script>

<style lang="scss" scoped>
  .container-icon{
    font-family: 'Roboto', sans-serif;
    background-color: #0282F9;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 200px;

    ul{
      list-style: none;
      display: flex;
      align-items: center;
      justify-content: space-around;
      gap: 2rem;

      a{
        text-decoration: none;
        color: white;
      }
    }
  };
</style>
