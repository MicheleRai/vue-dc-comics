<template>
  <footer>
    <div class="footer-container">
      <div>
        <h3>DC COMICS</h3>
        <ul>
          <li><a href="!">Characters</a></li>
          <li><a href="!">Comics</a></li>
          <li><a href="!">Movie</a></li>
          <li><a href="!">TV</a></li>
          <li><a href="!">Games</a></li>
          <li><a href="!">Videos</a></li>
          <li><a href="!">News</a></li>
        </ul>
        <h3>SHOP</h3>
        <ul>
          <li><a href="!">Shop DC</a></li>
          <li><a href="!">Shop DC Collectibles</a></li>
        </ul>
      </div>
      <div>
        <h3>DC</h3>
        <ul>
          <li><a href="!">Therms Of Use</a></li>
          <li><a href="!">Privacy policy(New)</a></li>
          <li><a href="!">Ad Choices</a></li>
          <li><a href="!">Advertising</a></li>
          <li><a href="!">Jobs</a></li>
          <li><a href="!">Subscriptions</a></li>
          <li><a href="!">Talent Workshops</a></li>
          <li><a href="!">CPSC Certificates</a></li>
          <li><a href="!">Ratings</a></li>
          <li><a href="!">Shop Help</a></li>
          <li><a href="!">Contact Us</a></li>
        </ul>
      </div>
      <div>
        <h3>SITES</h3>
        <ul>
          <li><a href="!">DC</a></li>
          <li><a href="!">MAD Magazine</a></li>
          <li><a href="!">DC Kids</a></li>
          <li><a href="!">DC Universe</a></li>
          <li><a href="!">DC Power Visa</a></li>
        </ul>
      </div>
    </div>
    <div class="social-container">
      <button>SIGN-UP NOW!</button>
      <div>
        <span>FOLLOW US</span>
        <img src="img\footer-facebook.png" alt="facebook">
        <img src="img\footer-periscope.png" alt="periscope">
        <img src="img\footer-pinterest.png" alt="pinterserest">
        <img src="img\footer-twitter.png" alt="twitter">
        <img src="img\footer-youtube.png" alt="youtube">
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'footerPage',
};
</script>

<style lang="scss" scoped>
  footer{
    background: black;
    //background-image: url(img\dc-logo-bg.png), url(vue-dc-comics/img/footer-bg.jpg) ;
    background-position: right center, center;
    background-repeat: no-repeat, no-repeat;
    background-size: auto, cover;
    color: white;
    margin: auto;
    padding:2rem 5rem ;

    .footer-container{
      display: flex;
      max-width: 900px;
      margin: auto;
      gap: 3rem;

      h3{
        margin-top: 1rem;
      };

      ul{
        list-style: none;

        a{
          text-decoration: none;
          color: #959595;
        };
      };
      .social-container{
        background-color: #303030;
        height: 100px;
        width: 300px;
        display: flex;
        justify-content: space-around;
        align-items: center;
      };
    };
  };
</style>
