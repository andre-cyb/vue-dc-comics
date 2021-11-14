<template>
  <div id="app">
    <Header></Header>
    <Main></Main>
    <!-- <SingleCard></SingleCard> -->
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
/* import SingleCard from "./components/SingleCard.vue"; */

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
    /*  SingleCard, */
  },
  data() {
    return {};
  },
};
</script>

<style lang="scss">
@import "styles/header";
@import "styles/main";
@import "styles/footer";
/* @import "styles/singleCard";
@import "styles/global"; */

#app {
  font-family: "PT Sans Narrow", sans-serif;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
</style>
