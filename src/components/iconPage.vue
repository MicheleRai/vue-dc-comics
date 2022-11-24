<template>
  <div class="container-icon">
    <ul>
      <li><a href="!"><img src="img/buy-comics-digital-comics.png" alt="1"><span>DIGITAL COMICS</span></a></li>
      <li><a href="!"><img src="img/buy-comics-merchandise.png" alt="1"><span>DC MERCHANDISE</span></a></li>
      <li><a href="!"><img src="img/buy-comics-subscriptions.png" alt="1"><span> SUBSCRIPTION</span></a></li>
      <li><a href="!"><img src="img/buy-comics-shop-locator.png" alt="1"><span>COMIC SHOP LOCATOR</span></a></li>
      <li><a href="!"><img src="img/buy-dc-power-visa.svg" alt="1"><span>DC POWER VISA</span></a></li>
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
      gap: 5rem;
      height: 100%;

      li{
        height: 100%;

        a{
          text-decoration: none;
          color: white;
          display: flex;
          align-items: center;
          gap: 1rem;
          border-bottom: 5px solid #0282F9;
          height: 100%;

          &:hover{
            border-color: white;
          };

          img{
            height: 80px;
          };
        };
      };
    };
  };
</style>
