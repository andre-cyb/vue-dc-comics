<template>
  <div class="my_footer">
    <div class="blue_section">
      <div class="my_cont_bluebar">
        <ul>
          <li>
            <img src="../img/buy-comics-digital-comics.png" alt="" />
            <a href="">DIGITAL COMICS</a>
          </li>
          <li>
            <img src="../img/buy-comics-merchandise.png" alt="" />
            <a href="">DIGITAL COMICS</a>
          </li>
          <li>
            <img src="../img/buy-comics-shop-locator.png" alt="" />
            <a href="">DIGITAL COMICS</a>
          </li>
          <li>
            <img src="../img/buy-comics-subscriptions.png" alt="" />
            <a href="">DIGITAL COMICS</a>
          </li>
          <li>
            <img src="" alt="" />
            <a href="">DIGITAL COMICS</a>
          </li>
        </ul>
      </div>
    </div>
    <div class="menu_section">
      <div class="my_cont_footer layout_menu_footer">
        <div class="my_col_4 container_menu">
          <div class="my_col_4">
            <ul class="list_style">
              <li class="menu_title_footer">DC COMICS</li>
              <li><a href="#">characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul>
            <ul class="list_style">
              <li class="menu_title_footer">SHOP</li>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
          </div>
          <div class="my_col_4">
            <ul class="list_style">
              <li class="menu_title_footer">DC</li>
              <li><a href="#">Terms Of Use</a></li>
              <li><a href="#">Privacy Policy (New)</a></li>
              <li><a href="#">Ad Choises</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Subscriptions</a></li>
              <li><a href="#">Talent Workshops</a></li>
              <li><a href="#">CPSC Certificates</a></li>
              <li><a href="#">Ratings</a></li>
              <li><a href="#">Shop Help</a></li>
              <li><a href="#">Contact Us</a></li>
            </ul>
          </div>
          <div class="my_col_4">
            <ul class="list_style">
              <li class="menu_title_footer">SITES</li>
              <li><a href="#">DC</a></li>
              <li><a href="#">MAD Magazine</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">DC Power Visa</a></li>
            </ul>
          </div>
        </div>
        <div class="dc_logo_bg my_col_8"></div>
      </div>
    </div>
    <div class="social_section">
      <div class="my_cont_footer_social">
        <button class="btn_footer">SIGN-UP-NOW!</button>
        <div class="social_cont">
          <h3>FOLLOW US</h3>
          <img src="../img/footer-facebook.png" alt="" />
          <img src="../img/footer-twitter.png" alt="" />
          <img src="../img/footer-youtube.png" alt="" />
          <img src="../img/footer-pinterest.png" alt="" />
          <img src="../img/footer-periscope.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.my_footer {
  background-color: blanchedalmond;
}
/* BLUE SECTION */
.my_cont_bluebar {
  margin: auto;
  max-width: 1140px;
}
.my_cont_footer {
  display: flex;
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
}
/* ************ */

/* MENU SECTION */
.menu_section {
  background-image: url(../img/footer-bg.jpg);
  object-fit: cover;
}
.layout_menu_footer {
  display: flex;
}

.container_menu {
  display: flex;
}

.dc_logo_bg {
  background-image: url(../img/dc-logo-bg.png);
  background-position: center;
  background-repeat: no-repeat;
}
.my_col_4 {
  width: calc((100% / 12) * 4);
}
.my_col_8 {
  width: calc((100% / 12) * 8);
}
.my_col_12 {
  width: calc((100% / 12) * 12);
}
.list_style {
  list-style: none;
  padding: 0px;
}
.list_style a {
  color: rgb(255, 255, 255);
  font-size: 13px;
  text-decoration: none;
}
.menu_title_footer {
  font-size: 20px;
  padding-bottom: 10px;
  color: white;
}
/* *********************** */

/* SOCIAL SECTION */
.my_cont_footer_social {
  display: flex;
  margin: auto;
  max-width: 1140px;
  align-items: center;
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
  padding-left: 10px;
}
.btn_footer {
  height: 40px;
}
.social_cont {
  display: inline-block;
  margin-left: auto;
}
/* *********************** */
</style>
