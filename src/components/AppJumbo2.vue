<template>
  <div class="fluid-container">
    <div class="row row-cols-4 g-0">
      <div class="col">
        <img src="../assets/img/gallery_01.jpg" alt="" />
      </div>
      <div class="col">
        <img src="../assets/img/gallery_02.jpg" alt="" />
      </div>
      <div class="col">
        <img src="../assets/img/gallery_03.jpg" alt="" />
      </div>
      <div class="col">
        <img src="../assets/img/gallery_04.jpg" alt="" />
      </div>
    </div>
    <div class="info_section">
      <div class="container">
        <div class="row">
          <div class="col-8 d-flex justify-content-center">
            <h2>See Our Kindergarten Photo Gallery!</h2>
          </div>
          <div class="col-4 d-flex justify-content-start">
            <div class="border_btn">
              <button class="btn ms_btn">View Gallery</button>
              <img src="../assets/img/slider_next.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppJumbo2",
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";

.info_section {
  width: 100%;
  height: 120px;
  line-height: 120px;
  background-image: url("../assets/img/pattern.png");

  h2 {
    line-height: 120px;
    font-weight: lighter;
    color: $sugar-cane;
  }

  .border_btn {
    width: 170px;
    height: 50px;
    border: 2px solid $sugar-cane;
    display: flex;
    justify-content: center;
    align-items: center;
    align-self: center;
    .ms_btn {
      text-transform: uppercase;
      font-weight: 400;
      color: $sugar-cane;
    }
    img {
      width: 30px;
      margin-left: -0.75rem;
    }
  }
}
</style>
