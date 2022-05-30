<template>
  <div id="app">
    <AppHeader :navArray="headerArray" />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
export default {
  name: "App",
  components: {
    AppHeader,
  },
  data: function () {
    return {
      headerArray: [
        {
          image: "home-2.png",
          title: "Home",
          active: true,
        },
        {
          image: "document.png",
          title: "Pages",
          active: false,
        },
        {
          image: "printer.png",
          title: "Blog",
          active: false,
        },
        {
          image: "cart.png",
          title: "Shop",
          active: false,
        },
        {
          image: "lab.png",
          title: "Shortcodes",
          active: false,
        },
        {
          image: "chat.png",
          title: "Support",
          active: false,
        },
        {
          image: "envelope.png",
          title: "Contact",
          active: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";
@import "./style/variables.scss";
</style>
