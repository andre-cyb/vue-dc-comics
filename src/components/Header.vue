<template>
  <div>
    <div class="my_header">
      <img src="../img/dc-logo.png" alt="" />
      <nav class="my_navbar">
        <ul>
          <li v-for="(item, i) in navBarItems" :key="i">
            <a href="item.href">{{ item.text }}</a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      navBarItems: [
        {
          text: "CHARACTERS",
          href: "#",
        },
        {
          text: "COMICS",
          href: "#",
        },
        {
          text: "MOVIES",
          href: "#",
        },
        {
          text: "TV",
          href: "#",
        },
        {
          text: "GAMES",
          href: "#",
        },
        {
          text: "COLLECTIBLES",
          href: "#",
        },
        {
          text: "VIDEOS",
          href: "#",
        },
        {
          text: "FANS",
          href: "#",
        },
        {
          text: "NEWS",
          href: "#",
        },
        {
          text: "SHOP",
          href: "#",
        },
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.my_header {
  background-color: silver;
}
.my_navbar {
  display: inline-block;
}
.my_navbar ul li {
  display: inline-block;
  padding: 10px;
}
</style>

