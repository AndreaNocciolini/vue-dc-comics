<template>
  <div class="container">
      <div class="jumbo-top"></div>
      <div class="ad-new-series">CURRENT SERIES</div>
      <div class="main-content">
        <div class="inner-main-content">
          <Cards v-for="(element, index) in products"
            :key="index"
            :srcImage="element.thumb"
            :title="element.series"
          />
        </div>
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
import Cards from "./Cards.vue"

export default {
    name: 'Main',
    components: {
      Cards,
    },
    data () {
        return {
            products : [
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
              price: "$19.99",
              series: "Action Comics",
              type: "comic book"
            },
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
              price: "$3.99",
              series: "American Vampire 1976",
              type: "comic book"
            },
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
              price: "$16.99",
              series: "Aquaman",
              type: "graphic novel"
            },
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
              price: "$2.99",
              series: "Batgirl",
              type: "comic book"
            },
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
              price: "$3.99",
              series: "Batman",
              type: "comic book"
            },
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
              price: "$2.99",
              series: "Batman Beyond",
              type: "comic book"
            },
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
              price: "$3.99",
              series: "Batman/Superman",
              type: "comic book"
            },
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
              price: "$4.99",
              series: "Batman/Superman Annual",
              type: "comic book"
            },
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
              price: "$5.99",
              series: "Batman: The Joker War Zone",
              type: "comic book"
            },
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
              price: "$6.99",
              series: "Batman: Three Jokers",
              type: "comic book"
            },
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
              price: "$4.99",
              series: "Batman: White Knight Presents: Harley Quinn",
              type: "comic book"
            },
            {
              thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
              price: "$16.99",
              series: "Catwoman",
              type: "graphic novel"
            }
          ]
        }
    }
}
</script>

<style lang="scss">
    .container {
        width: 100%;
        background-color: black;
        color: white;
        position: relative;
        .jumbo-top {
          background-image: url(../assets/img/jumbotron.jpg);
          background-size: cover;
          width: 100%;
          height: 300px;
        }
        .ad-new-series {
          position: absolute;
          top: 283px;
          left: 130px;  
          background-color: #0c7cec;
          padding: 0.6em;
          box-shadow: 5px 1px 5px 2px #0059FF;
        }
        .main-content {
            padding: 4em;
            background-color: black;
            h2 {
                margin: 0;
                padding: 2em;
            }
            .inner-main-content{
                display: flex;
                flex-wrap: wrap;
                justify-content: space-around;
                width: 80%;
                margin: 0 auto;
                gap: 0.5em;
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