<template>
  <div class="container-footer">
      <div class="inner-container-sx">
          <div class="links-container">
              <div>
                  <div>
                    <ul>
                        <h3>DC COMICS</h3>
                        <li><a href="">Characters</a></li>
                        <li><a href="">Comics</a></li>
                        <li><a href="">Movies</a></li>
                        <li><a href="">TV</a></li>
                        <li><a href="">Games</a></li>
                        <li><a href="">Videos</a></li>
                        <li><a href="">News</a></li>
                    </ul>
                  </div>
                <div>
                    <ul>
                        <h3>SHOP</h3>
                        <li><a href="">Shop DC</a></li>
                        <li><a href="">Shop DC Collectibles</a></li>
                    </ul>
                </div>
            </div>
              
            <div>
                <ul>
                    <h3>DC</h3>
                    <li><a href="">Terms Of Use</a></li>
                    <li><a href="">Privacy policy (New)</a></li>
                    <li><a href="">Ad Choices</a></li>
                    <li><a href="">Advertising</a></li>
                    <li><a href="">Jobs</a></li>
                    <li><a href="">Subscriptions</a></li>
                    <li><a href="">Talent Workshops</a></li>
                    <li><a href="">CPSC Certificates</a></li>
                    <li><a href="">Ratings</a></li>
                    <li><a href="">Shop Help</a></li>
                    <li><a href="">Contact Us</a></li>
                </ul>
            </div>
            <div>
                <ul>
                    <h3>SITES</h3>
                    <li><a href="">DC</a></li>
                    <li><a href="">MAD Magazine</a></li>
                    <li><a href="">DC Kids</a></li>
                    <li><a href="">DC Universe</a></li>
                    <li><a href="">DC Power Vise</a></li>
                </ul>
            </div>
          </div>

          <div class="inner-container-dx">
              <!-- Empty <div>, used for logo DC big -->
          </div>
      </div>
      <div class="footer-menu">
          <div>
              <button>SIGN UP NOW</button>
          </div>

          <div class="footer-social">
              <h3>FOLLOW US</h3>
              <ul>
                  <li><a href=""><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                  <li><a href=""><img src="../assets/img/footer-periscope.png" alt=""></a></li>
                  <li><a href=""><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                  <li><a href=""><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                  <li><a href=""><img src="../assets/img/footer-youtube.png" alt=""></a></li>
              </ul>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    .container-footer {
        width: 100%;
        margin: 0;
        background-image: url(../assets/img/footer-bg.jpg);
        .inner-container-sx {
            display: flex;
            .links-container{
                width: 50%;
                display: flex;
                }
        }
        ul{ 
            margin: 0;
            padding: 1em;
            list-style-type: none;
            h3{
                margin: 0;
            }
            a {
                text-decoration: none;
                color: grey;
            }
        }
        .inner-container-dx {
            width: 50%;
            background-image: url(../assets/img/dc-logo-bg.png);
            background-repeat: no-repeat;
            background-size: 55%;
            background-position: center;
        }
        .footer-menu {
            display: flex;
            align-items: center;
            justify-content: space-around;
            background-color: #303030;
            padding: 1em;
            button {
                background: #303030;
                border-color: #0282F9;
                border-style: solid;
                border-width: 2px;
                color: #fff;
                display: inline-block;
                font-size: 20px;
                height: 50px;
                text-align: center;
                text-transform: uppercase;
                transition-duration: .3s;
                transition-property: background-color;
                transition-timing-function: ease;
                width: 150px;
            }
            .footer-social{
                display: flex;
            }
            ul{
                list-style-type: none;
                display: flex;
                gap: 0.5em;
                li a{
                    text-decoration: none;
                }
            }
            h3 {
                display: inline-block;
                color: #0282f9;
            }
        }
    }
</style>