<template>
  <div class="fluid-container">
    <div class="map_card">
      <img
        v-for="(item, index) in maps"
        :key="index"
        :src="require(`../assets/img/${maps[index].image}`)"
        alt=""
      />
      <div class="google_banner">
        <img src="../assets/img/google4.png" alt="" />
      </div>
      <div class="maps_thumbs text-center">
        <h1>+</h1>
        <h1>-</h1>
      </div>
      <div class="directions_banner">
        <img src="../assets/img/cattura.jpg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppSection9",
  props: {
    maps: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";

.map_card {
  position: relative;
  img {
    width: calc(100% / 9);
  }
  .google_banner {
    position: absolute;
    bottom: 5%;
    right: 48%;
    img {
      width: 120px;
    }
  }
  .maps_thumbs {
    position: absolute;
    bottom: 3%;
    right: 0.5%;
    h1 {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 0.3rem 0.7rem;
      font-size: 2rem;
      margin: 0.2rem 0;
      color: $tuatara;
      background-color: $sugar-cane;
      cursor: pointer;
    }
  }
  .directions_banner {
    position: absolute;
    top: 3%;
    left: 1%;
    img {
      width: 300px;
    }
  }
}
</style>
