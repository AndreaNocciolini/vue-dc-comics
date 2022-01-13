<template>
  <div class="container">
      <div class="main-content">
          <h2>-->Content Goes Here</h2>
      </div>
      <div class="main-end-menu">
          <ul>
              <li><a href=""><img src="../assets/img/buy-comics-digital-comics.png" alt=""><span>DIGITAL COMICS</span></a></li>
              <li><a href=""><img src="../assets/img/buy-comics-merchandise.png" alt=""><span>DC MERCHANDISE</span></a></li>
              <li><a href=""><img src="../assets/img/buy-comics-subscriptions.png" alt=""><span>SUBSCRIPTION</span></a></li>
              <li><a href=""><img class="location-logo" src="../assets/img/buy-comics-shop-locator.png" alt=""><span>COMIC SHOP LOCATION</span></a></li>
              <li><a href=""><img src="../assets/img/buy-dc-power-visa.svg" alt=""><span>DC POWER VISA</span></a></li>
          </ul>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Main',
}
</script>

<style lang="scss">
    .container {
        width: 100%;
        background-color: black;
        color: white;
        .main-content {
            background-color: black;
            h2 {
                margin: 0;
                padding: 2em;
            }
        }
        .main-end-menu {
            background-color: #0282f9;
            ul {
                width: 80%;
                margin: 0 auto;
                padding: 1em;
                display: flex;
                align-items: center;
                justify-content: space-around;
                list-style: none;
                li {
                    img{
                        width: 3em;
                    }
                    .location-logo{
                        width: 2em;
                    }
                    span {
                        font-size: 0.7em;
                    }
                    a {
                        display: flex;
                        align-items: center;
                        text-decoration: none;
                        color: white;
                        gap: 0.5em;
                    }
                }
            }
        }
    }
</style>