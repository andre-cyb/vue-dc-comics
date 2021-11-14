<template>
  <div class="my_header">
    <div class="my_cont_header">
      <img class="logo" src="@/assets/dc-logo.png" alt="" />
      <nav class="my_navbar">
        <ul>
          <li v-for="(item, i) in navBarItems" :key="i">
            <a
              href="item.href"
              @click.prevent="activeElement = i"
              :class="i === activeElement ? 'active' : ''"
              >{{ item.text }}</a
            >
            <div
              class="barra"
              :style="i === activeElement ? 'opacity: 1' : ''"
            ></div>
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
      activeElement: 0,
    };
  },
};
</script>


<style>
</style>

