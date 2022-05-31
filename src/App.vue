<template>
  <div id="app">
    <AppHeader :navArray="headerArray" />
    <main>
      <AppMain />
    </main>
    <AppFooter
      :archives="archivesArray"
      :features="featuresArray"
      :posts="postsArray"
      :socials="socialsArray"
    />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppMain,
    AppFooter,
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
      archivesArray: [
        {
          month: "october",
          year: 2014,
          documents: "(2)",
        },
        {
          month: "september",
          year: 2014,
          documents: "(2)",
        },
        {
          month: "august",
          year: 2014,
          documents: "(2)",
        },
        {
          month: "july",
          year: 2014,
          documents: "(2)",
        },
        {
          month: "june",
          year: 2014,
          documents: "(2)",
        },
        {
          month: "may",
          year: 2014,
          documents: "(1)",
        },
      ],
      featuresArray: [
        {
          image: "style_4_alt.png",
          feature: "Friendly and welcoming place",
        },
        {
          image: "style_4_alt.png",
          feature: "Science and art classes",
        },
        {
          image: "style_4_alt.png",
          feature: "Positive learning environment",
        },
        {
          image: "style_4_alt.png",
          feature: "Educational field trips",
        },
        {
          image: "style_4_alt.png",
          feature: "Writing and reading classes",
        },
        {
          image: "style_4_alt.png",
          feature: "Science and art classes",
        },
      ],
      postsArray: [
        {
          postImage: "blog_09-150x150.jpg",
          title: "Drawing and Painting Lessons",
          dateImg: "date_footer.png",
          dateTxt: "October 03, 2014",
        },
        {
          postImage: "blog_10-150x150.jpg",
          title: "Fall Parents Meeting Day",
          dateImg: "date_footer.png",
          dateTxt: "October 03, 2014",
        },
        {
          postImage: "blog_08-150x150.jpg",
          title: "Birthday in Kindergarten",
          dateImg: "date_footer.png",
          dateTxt: "September 20, 2014",
        },
      ],
      socialsArray: [
        "behance.png",
        "dribbble.png",
        "envato.png",
        "facebook.png",
        "twitter.png",
      ],
    };
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";
@import "./style/variables.scss";
</style>
