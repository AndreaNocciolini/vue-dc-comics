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
    }
</style>