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
    <div class="menu_section">aa</div>
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
.my_cont_footer {
  margin: auto;
  max-width: 1140px;
}
.my_cont_footer ul {
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
}
.blue_section ul li {
  display: inline-block;
  padding: 10px;
}
.blue_section ul li a {
  color: black;
  font-size: 13px;
  text-decoration: none;
}
</style>
