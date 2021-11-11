<template>
  <div class="my_footer">
    <div class="blue_section">
      <div class="my_cont_footer">
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
        <div class="my_col_4">
          <ul>
            <li>asdasd</li>
            <li>asdasd</li>
            <li>asdasd</li>
            <li>asdasd</li>
          </ul>
          <ul>
            <li>asdasd</li>
            <li>asdasd</li>
            <li>asdasd</li>
            <li>asdasd</li>
          </ul>
          <ul>
            <li>asdasd</li>
            <li>asdasd</li>
            <li>asdasd</li>
            <li>asdasd</li>
          </ul>
        </div>
        <div class="dc_logo_bg my_col_8"></div>
      </div>
    </div>
    <div class="social_section">aa</div>
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
.my_cont_footer {
  margin: auto;
  max-width: 1140px;
}
.blue_section .my_cont_footer ul {
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

.menu_section {
  background-image: url(../img/footer-bg.jpg);
  object-fit: cover;
}
.layout_menu_footer {
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
</style>
