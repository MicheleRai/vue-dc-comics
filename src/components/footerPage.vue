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
      <div class="social-content">
        <button>SIGN-UP NOW!</button>
        <div class="social-icon">
          <span>FOLLOW US:</span>
          <a href="!"><img
            src="img\footer-facebook.png"
            alt="facebook"
          ></a>
          <a href="!"><img
            src="img\footer-periscope.png"
            alt="periscope"
          ></a>
          <a href="!"><img
            src="img\footer-pinterest.png"
            alt="pinterserest"
          ></a>
          <a href="!"><img
            src="img\footer-twitter.png"
            alt="twitter"
          ></a>
          <a href="!"><img
            src="img\footer-youtube.png"
            alt="youtube"
          ></a>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterPage',
};
</script>

<style lang="scss" scoped>
  footer{
    font-family: 'Roboto', sans-serif;
    background: black;
    background-image: url(../../public/img/footer-bg.jpg) ;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    color: white;
    display: flex;
    flex-direction: column;

    .footer-container{
      background-image: url(../../public/img/dc-logo-bg.png);
      background-position: right center;
      background-repeat: no-repeat;
      background-size: auto;
      display: flex;
      gap: 3rem;
      padding-top: 2rem;
      max-width: 1200px;
      width: 100%;
      margin: auto;
      padding-bottom: 2rem;

      h3{
        margin-top: 1rem;
      };

      ul{
        list-style: none;
        line-height: 1.5rem;

        a{
          text-decoration: none;
          color: #959595;

          &:hover{
            color: #0282F9;
          }
        };
      };
    };
    .social-container{
        background-color: #303030;
        height: 100px;
        display: flex;
        align-items: center;
        padding: auto 20rem;

       .social-content{
        max-width: 1200px;
        width: 100%;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        flex-wrap: nowrap;
          button{
            color: white;
            background-color: #303030;
            border-color: #0282F9;
            padding: 9px 5px;

            &:hover{
              background-color: white;
              color: black;
            }
          }
          .social-icon{
            display: flex;
            align-items: center;
            gap: 1.7rem;

            span{
              color: #0282F9
            };
            img{
              cursor: pointer;
              border: 3px solid #303030;
              border-radius: 100%;

              &:hover{
                border-color: #0282F9;
                background-color: white;
              };
            };
          };
        };
      };
  };
</style>
