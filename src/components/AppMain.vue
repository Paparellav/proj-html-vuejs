<template>
  <div>
    <section>
      <AppJumbo />
    </section>
    <section>
      <AppSectionOne />
    </section>
  </div>
</template>

<script>
import AppJumbo from "./AppJumbo.vue";
import AppSectionOne from "./AppSectionOne.vue";

export default {
  name: "AppMain",
  components: {
    AppJumbo,
    AppSectionOne,
  },
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";
</style>
