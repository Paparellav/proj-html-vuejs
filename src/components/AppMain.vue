<template>
  <div>
    <section>
      <AppJumbo />
    </section>
    <section>
      <AppSection1 />
    </section>
    <section class="mt-5">
      <AppSection2 />
    </section>
    <section>
      <AppSection3 />
    </section>
    <section class="mt-5 mb-5">
      <AppSection4 />
    </section>
    <section>
      <AppSection5 />
    </section>
    <section>
      <AppJumbo2 />
    </section>
    <section class="mt-5 mb-5">
      <AppSection6 />
    </section>
    <section>
      <AppSection7 />
    </section>
    <section class="mt-5 mb-5">
      <AppSection8 />
    </section>
    <section>
      <AppSection9 :maps="mapArray" />
    </section>
    <section class="mt-5 mb-5">
      <AppSection10 />
    </section>
  </div>
</template>

<script>
import AppJumbo from "./AppJumbo.vue";
import AppSection1 from "./AppSection1.vue";
import AppSection2 from "./AppSection2.vue";
import AppSection3 from "./AppSection3.vue";
import AppSection4 from "./AppSection4.vue";
import AppSection5 from "./AppSection5.vue";
import AppJumbo2 from "./AppJumbo2.vue";
import AppSection6 from "./AppSection6.vue";
import AppSection7 from "./AppSection7.vue";
import AppSection8 from "./AppSection8.vue";
import AppSection9 from "./AppSection9.vue";
import AppSection10 from "./AppSection10.vue";

export default {
  name: "AppMain",
  components: {
    AppJumbo,
    AppSection1,
    AppSection2,
    AppSection3,
    AppSection4,
    AppSection5,
    AppJumbo2,
    AppSection6,
    AppSection7,
    AppSection8,
    AppSection9,
    AppSection10,
  },
  data: function () {
    return {
      mapArray: [
        {
          image: "vt (21).png",
          name: "image-1",
        },
        {
          image: "vt (17).png",
          name: "image-2",
        },
        {
          image: "vt (14).png",
          name: "image-3",
        },
        {
          image: "vt (4).png",
          name: "image-4",
        },
        {
          image: "vt (1).png",
          name: "image-5",
        },
        {
          image: "vt (3).png",
          name: "image-6",
        },
        {
          image: "vt (12).png",
          name: "image-7",
        },
        {
          image: "vt (18).png",
          name: "image-8",
        },
        {
          image: "vt (23).png",
          name: "image-9",
        },
        {
          image: "vt (24).png",
          name: "image-10",
        },
        {
          image: "vt (16).png",
          name: "image-11",
        },
        {
          image: "vt (13).png",
          name: "image-12",
        },
        {
          image: "vt.png",
          name: "image-13",
        },
        {
          image: "vt (2).png",
          name: "image-14",
        },
        {
          image: "vt (5).png",
          name: "image-15",
        },
        {
          image: "vt (10).png",
          name: "image-16",
        },
        {
          image: "vt (19).png",
          name: "image-17",
        },
        {
          image: "vt (25).png",
          name: "image-18",
        },
        {
          image: "vt (22).png",
          name: "image-19",
        },
        {
          image: "vt (15).png",
          name: "image-20",
        },
        {
          image: "vt (8).png",
          name: "image-21",
        },
        {
          image: "vt (9).png",
          name: "image-22",
        },
        {
          image: "vt (6).png",
          name: "image-23",
        },
        {
          image: "vt (7).png",
          name: "image-24",
        },
        {
          image: "vt (11).png",
          name: "image-25",
        },
        {
          image: "vt (20).png",
          name: "image-26",
        },
        {
          image: "vt (26).png",
          name: "image-27",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";
</style>
