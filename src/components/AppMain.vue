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
  },
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";
</style>
