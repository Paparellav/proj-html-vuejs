<template>
  <div class="fluid-container">
    <div class="ms_container">
      <div class="first-image text-center">
        <img src="../assets/img/slider_slide3_img2.png" alt="" />
      </div>
      <div class="second-image text-center">
        <img src="../assets/img/slider_slide3_img3.png" alt="" />
      </div>
    </div>
    <div class="info_section">
      <div class="container">
        <div class="row">
          <div class="col-8 d-flex justify-content-center">
            <h2>How to Enroll Your Child to a Class?</h2>
          </div>
          <div class="col-4 d-flex justify-content-start">
            <div class="border_btn">
              <button class="btn ms_btn">Learn more</button>
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
  name: "AppJumbo",
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";
.ms_container {
  height: 450px;
  background-image: url("../assets/img/slider_slide3_background.png");
  background-size: contain;
  background-position: center;
  position: relative;

  .first-image {
    img {
      width: 200px;
      position: absolute;
      bottom: 10%;
      left: 40%;
    }
  }

  .second-image {
    img {
      width: 120px;
      position: absolute;
      bottom: 8%;
      right: 23%;
    }
  }
}

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
    width: 160px;
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
