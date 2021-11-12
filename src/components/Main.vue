<template>
  <div class="my_main">
    <div class="my_cont_main">
      <SingleCard></SingleCard>
    </div>
  </div>
</template>

<script>
import SingleCard from "./SingleCard.vue";
export default {
  name: "Main",
  component: {
    SingleCard,
  },
};
</script>


<style>
/* @import "./styles/main"; */
/* .my_main {
  padding: 20px 0px 20px 0px;
  background-color: rgb(0, 0, 0);
}
.my_cont_main {
  display: flex;
  margin: auto;
  max-width: 1140px;
}
.main_title {
  color: white;
} */
</style>
