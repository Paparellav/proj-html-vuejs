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
  </div>
</template>

<script>
import AppJumbo from "./AppJumbo.vue";
import AppSectionOne from "./AppSectionOne.vue";
import AppSectionTwo from "./AppSectionTwo.vue";

export default {
  name: "AppMain",
  components: {
    AppJumbo,
    AppSectionOne,
    AppSectionTwo,
  },
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";
</style>
