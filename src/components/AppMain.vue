<template>
  <AppJumbo />
</template>

<script>
import AppJumbo from "./AppJumbo.vue";

export default {
  name: "AppMain",
  components: {
    AppJumbo,
  },
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";
</style>
