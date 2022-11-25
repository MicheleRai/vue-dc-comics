<template>
  <div class="container-icon">
    <div class="content-icon">
      <ul>
        <li>
          <a href="!"><img
            src="img/buy-comics-digital-comics.png"
            alt="1"
          ><span>DIGITAL COMICS</span></a>
        </li>
        <li>
          <a href="!"><img
            src="img/buy-comics-merchandise.png"
            alt="1"
          ><span>DC MERCHANDISE</span></a>
        </li>
        <li>
          <a href="!"><img
            src="img/buy-comics-subscriptions.png"
            alt="1"
          ><span> SUBSCRIPTION</span></a>
        </li>
        <li>
          <a href="!"><img
            src="img/buy-comics-shop-locator.png"
            alt="1"
          ><span>COMIC SHOP LOCATOR</span></a>
        </li>
        <li>
          <a href="!"><img
            src="img/buy-dc-power-visa.svg"
            alt="1"
          ><span>DC POWER VISA</span></a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IconPage',
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

    .content-icon{
    max-width: 1200px;
      ul{
      list-style: none;
      display: flex;
      flex-wrap: nowrap;
      align-items: center;
      justify-content: space-around;
      gap: 5rem;
      height: 100%;

      li{
        height: 100%;
        flex: 0 0 20%;
        padding: 4rem 0;
        border-bottom: 5px solid #0282F9;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;

        &:hover{
          border-color: white;
        };

        a{
          text-decoration: none;
          color: white;
          display: flex;
          flex-wrap: nowrap;
          align-items: center;
          gap: 1rem;
          height: 100%;

          img{
            height: 80px;
          };
        };
      };
      };
    };
  }
</style>
