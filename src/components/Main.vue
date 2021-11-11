<template>
  <div class="my_main">
    <div class="my_cont_main">
      <h2 class="main_title">CONTENT GOES HERE</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.my_main {
  background-color: rgb(0, 0, 0);
}
.my_cont_main {
  background-color: rgb(26, 26, 26);
  display: flex;
  margin: auto;
  max-width: 1140px;
}
.main_title {
  color: white;
}
</style>
