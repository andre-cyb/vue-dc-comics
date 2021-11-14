<template>
  <div>
    <!-- card -->
    <div class="card_cont">
      <div class="cont_img">
        <img :src="img" alt="" />
      </div>
      <p>{{ title }}</p>
    </div>
    <!-- card -->
  </div>
</template>

<script>
export default {
  name: "SingleCard",
  props: ["img", "title"],
  data() {
    return {};
  },
};
</script>


<style lang="scss">
</style>
