<template>
  <div class="my_footer">
    <div class="blue_section">
      <div class="my_cont_bluebar">
        <ul>
          <li v-for="(item, i) in blueBarItems" :key="i">
            <img :src= require(`@/assets/${item.src}`) alt="" />
            <a href="">{{ item.text }}</a>
          </li>
          <!-- <li>
            <img src="@/assets/buy-comics-digital-comics.png" alt="" />
            <a href="">DIGITAL COMICS</a>
          </li>
          <li>
            <img src="@/assets/buy-comics-merchandise.png" alt="" />
            <a href="">DC MERCHANDISE</a>
          </li>
          <li>
            <img src="@/assets/buy-comics-shop-locator.png" alt="" />
            <a href="">SUBSCRIPTION</a>
          </li>
          <li>
            <img src="@/assets/buy-comics-subscriptions.png" alt="" />
            <a href="">COMIC SHOP LOCATOR</a>
          </li>
          <li>
            <img src="@/assets/buy-dc-power-visa.svg" alt="" />
            <a href="">DC POWER VISA</a>
          </li> -->
        </ul>
      </div>
    </div>
    <div class="menu_section">
      <div class="my_cont_footer">
        <div class="my_col_5 container_menu">
          <div class="my_col_5">
            <ul class="list_style">
              <li class="menu_title_footer">{{ dcComicMenu[0].title }}</li>
              <li v-for="(item, i) in dcComicMenu" :key="i">
                <a href="item.href">{{ item.text }}</a>
              </li>
            </ul>
            <ul class="list_style">
              <li class="menu_title_footer">{{ shopMenu[0].title }}</li>
              <li v-for="(item, i) in shopMenu" :key="i">
                <a href="item.href">{{ item.text }}</a>
              </li>
            </ul>
          </div>
          <div class="my_col_5">
            <ul class="list_style">
              <li class="menu_title_footer">{{ dcMenu[0].title }}</li>
              <li v-for="(item, i) in dcMenu" :key="i">
                <a href="item.href">{{ item.text }}</a>
              </li>
            </ul>
          </div>
          <div class="my_col_5">
            <ul class="list_style">
              <li class="menu_title_footer">{{ sitesMenu[0].title }}</li>
              <li v-for="(item, i) in sitesMenu" :key="i">
                <a href="item.href">{{ item.text }}</a>
              </li>
            </ul>
          </div>
        </div>
        <div class="dc_logo_bg my_col_7"></div>
      </div>
    </div>
    <div class="social_section">
      <div class="my_cont_footer_social">
        <button class="btn_footer">SIGN-UP-NOW!</button>
        <div class="social_cont">
          <h3>FOLLOW US</h3>
          <img src="@/assets/footer-facebook.png" alt="" />
          <img src="@/assets/footer-twitter.png" alt="" />
          <img src="@/assets/footer-youtube.png" alt="" />
          <img src="@/assets/footer-pinterest.png" alt="" />
          <img src="@/assets/footer-periscope.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      dcComicMenu: [
        {
          title: "DC COMICS",
          text: "",
          href: "",
        },
        {
          text: "characters",
          href: "#",
        },
        {
          text: "Comics",
          href: "#",
        },
        {
          text: "Movies",
          href: "#",
        },
        {
          text: "Tv",
          href: "#",
        },
        {
          text: "Games",
          href: "#",
        },
        {
          text: "Videos",
          href: "#",
        },
        {
          text: "News",
          href: "#",
        },
      ],
      shopMenu: [
        {
          title: "SHOP",
          text: "",
          href: "",
        },
        {
          text: "Shop DC",
          href: "#",
        },
        {
          text: "Shop DC Collectibles",
          href: "#",
        },
      ],
      dcMenu: [
        {
          title: "DC",
          text: "",
          href: "",
        },
        {
          text: "Terms Of Use",
          href: "#",
        },
        {
          text: "Privacy Policy (New)",
          href: "#",
        },
        {
          text: "Ad Choises",
          href: "#",
        },
        {
          text: "Advertising",
          href: "#",
        },
        {
          text: "Jobs",
          href: "#",
        },
        {
          text: "Subscriptions",
          href: "#",
        },
        {
          text: "Talent Workshops",
          href: "#",
        },
        {
          text: "CPSC Certificates",
          href: "#",
        },
        {
          text: "Ratings",
          href: "#",
        },
        {
          text: "Shop Help",
          href: "#",
        },
        {
          text: "Contact Us",
          href: "#",
        },
      ],
      sitesMenu: [
        {
          title: "SITES",
          text: "",
          href: "",
        },
        {
          text: "DC",
          href: "#",
        },
        {
          text: "MAD Magazine",
          href: "#",
        },
        {
          text: "DC Kids",
          href: "#",
        },
        {
          text: "DC Universe",
          href: "#",
        },
        {
          text: "DC Power Visa",
          href: "#",
        },
      ],
      blueBarItems: [
        {
          src: "buy-comics-digital-comics.png",
          text: "DIGITAL COMICS",
        },
        {
          src: "buy-comics-merchandise.png",
          text: "DC MERCHANDISE",
        },
        {
          src: "buy-comics-shop-locator.png",
          text: "SUBSCRIPTION",
        },
        {
          src: "buy-comics-subscriptions.png",
          text: "COMIC SHOP LOCATOR",
        },
        {
          src: "buy-dc-power-visa.svg",
          text: "DC POWER VISA",
        },
      ],
    };
  },
};
</script>


<style>
/* @import "./styles/footer"; */
/* FOOTER in CSS*/
/* .my_footer {
  background-color: blanchedalmond;
} */
/* *********** */
/* BLUE SECTION */
/* .my_cont_bluebar {
  margin: auto;
  max-width: 1140px;
}

.blue_section .my_cont_bluebar ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.blue_section {
  padding: 10px 0px 10px 0px;
  background-color: #0282f9;
}
.blue_section img {
  width: 40px;
  vertical-align: middle;
}
.blue_section ul li {
  display: inline-block;
  padding: 10px;
}
.blue_section ul li a {
  color: rgb(255, 255, 255);
  font-size: 13px;
  text-decoration: none;
  padding-left: 10px;
} */
/* ************ */

/* MENU SECTION */
/* .menu_section {
  background-image: url(../img/footer-bg.jpg);
  object-fit: cover;
}

.my_cont_footer {
  display: flex;
  margin: auto;
  max-width: 1140px;
}
.container_menu {
  display: flex;
  padding: 20px 0px 20px 0px;
}

.dc_logo_bg {
  background-image: url(../img/dc-logo-bg.png);
  background-position: center;
  background-repeat: no-repeat;
}
.my_col_5 {
  width: calc((100% / 12) * 5);
}
.my_col_7 {
  width: calc((100% / 12) * 7);
}
.list_style {
  list-style: none;
  padding: 0px;
}
.list_style li {
  padding-bottom: 4px;
}
.list_style a {
  color: #959595;
  font-size: 11px;
  text-decoration: none;
}
.menu_title_footer {
  font-size: 18px;
  padding-bottom: 10px;
  color: white;
} */
/* *********************** */

/* SOCIAL SECTION */
/* .my_cont_footer_social {
  display: flex;
  margin: auto;
  max-width: 1140px;
  align-items: center;
  padding: 15px 0px 15px 0px;
}
.social_section {
  background-color: #303030;
}
.social_section h3 {
  display: inline-block;
  vertical-align: middle;
  padding: 0px 10px 0px 10px;
  color: #0282f9;
}
.social_section img {
  vertical-align: middle;
  padding-left: 15px;
}
.btn_footer {
  padding: 10px;
  color: white;
  height: 40px;
  background-color: #303030;
  border: 2px solid #0282f9;
}
.social_cont {
  display: inline-block;
  margin-left: auto;
} */
/* *********************** */
</style>
