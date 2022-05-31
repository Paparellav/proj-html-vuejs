<template>
  <div>
    <section>
      <AppJumbo />
    </section>
    <section>
      <AppSectionOne />
    </section>
    <section class="mt-5">
      <AppSectionTwo />
    </section>
    <section>
      <AppSectionThree />
    </section>
    <section class="mt-5 mb-5">
      <AppSectionFourth />
    </section>
    <section>
      <AppSectionFifth />
    </section>
    <section>
      <AppJumbo2 />
    </section>
  </div>
</template>

<script>
import AppJumbo from "./AppJumbo.vue";
import AppSectionOne from "./AppSectionOne.vue";
import AppSectionTwo from "./AppSectionTwo.vue";
import AppSectionThree from "./AppSectionThree.vue";
import AppSectionFourth from "./AppSectionFourth.vue";
import AppSectionFifth from "./AppSectionFifth.vue";
import AppJumbo2 from "./AppJumbo2.vue";

export default {
  name: "AppMain",
  components: {
    AppJumbo,
    AppSectionOne,
    AppSectionTwo,
    AppSectionThree,
    AppSectionFourth,
    AppSectionFifth,
    AppJumbo2,
  },
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";
</style>
