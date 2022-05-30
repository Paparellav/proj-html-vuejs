<template>
  <div class="banner_section_3">
    <div class="container">
      <div class="row row-cols-4">
        <div class="col d-flex flex-column text-center">
          <div class="stats_circle">
            <h1>507</h1>
          </div>
          <h3>Our Pupils</h3>
          <small
            >Pulvinar forte maestro node <br />
            terminal est ellipsis prism.
          </small>
        </div>
        <div class="col d-flex flex-column text-center">
          <div class="stats_circle">
            <h1>235</h1>
          </div>
          <h3>Teaching Hours</h3>
          <small
            >Ellipsis morbi nulla a metro <br />
            interdum vitae elite.
          </small>
        </div>
        <div class="col d-flex flex-column text-center">
          <div class="stats_circle">
            <h1>100%</h1>
          </div>
          <h3>Satisfied Parents</h3>
          <small
            >Elementum pulvinar detos <br />
            diaspis movum blandit.
          </small>
        </div>
        <div class="col d-flex flex-column text-center">
          <div class="stats_circle">
            <h1>1050</h1>
          </div>
          <h3>Meals Per Year</h3>
          <small
            >Pulvinar forte maestro node <br />
            terminal est ellipsis prism.
          </small>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppSectionThree",
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";

.banner_section_3 {
  padding: 7rem 0;
  background-image: url("../assets/img/parallax_01.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  filter: grayscale(0.5);
  color: $sugar-cane;
  .stats_circle {
    width: 120px;
    height: 120px;
    margin: auto;
    margin-bottom: 1.2rem;
    border: 2px solid $sugar-cane;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    h1 {
      font-weight: lighter;
    }
  }
  h3 {
    font-weight: lighter;
    margin-bottom: 1rem;
  }
}
</style>
