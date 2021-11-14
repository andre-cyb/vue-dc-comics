<template>
  <div class="my_footer">
    <div class="blue_section">
      <div class="my_cont_bluebar">
        <ul>
          <li v-for="(item, i) in blueBarItems" :key="i">
            <img :src="require(`@/assets/${item.src}`)" alt="" />
            <a href="">{{ item.text }}</a>
          </li>
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
        <button class="btn_footer"><span>SIGN-UP-NOW!</span></button>
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
</style>
