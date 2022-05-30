<template>
  <div class="ms_section">
    <div class="container">
      <div class="row row-cols-2">
        <div class="col">
          <button class="mt-4 me-4 btn orange_btn">Overview</button>
          <button class="mt-4 btn secondary_btn">Our Mission</button>
          <h2 class="mt-5">
            Our philosophy is learning through <br />
            play as we offer a stimulating <br />
            environment for children.
          </h2>
          <div class="item_card d-flex mt-5">
            <div class="item_card_image me-4">
              <img src="../assets/img/clock_alt.png" alt="" />
            </div>
            <div class="item_card_text">
              <h5>Full Day Sessions</h5>
              <small>
                Pulvinar est metro ligula blandit maecenas retrum <br />
                gravida cuprum. Maecenas node estibulum.
              </small>
            </div>
          </div>
          <div class="item_card d-flex mt-5">
            <div class="item_card_image me-4">
              <img src="../assets/img/diagram_alt.png" alt="" />
            </div>
            <div class="item_card_text">
              <h5>Varied Classes</h5>
              <small>
                Pulvinar est metro ligula blandit maecenas retrum <br />
                gravida cuprum. Maecenas node estibulum.
              </small>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="primary_image">
            <div class="thumb thumb_prev">
              <img src="../assets/img/slider_previous.png" alt="" />
            </div>
            <img src="../assets/img/gallery_01.jpg" alt="" />
            <div class="thumb thumb_next">
              <img src="../assets/img/slider_next.png" alt="" />
            </div>
          </div>
          <div class="row row-cols-3 g-1 mt-2">
            <div class="col">
              <img src="../assets/img/gallery_07-690x506.jpg" alt="" />
            </div>
            <div class="col selected">
              <img src="../assets/img/gallery_01-690x506.jpg" alt="" />
            </div>
            <div class="col">
              <img src="../assets/img/gallery_08-690x506.jpg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppSectionTwo",
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";

.ms_section {
  background-color: $bon-jour;
  padding: 2rem 0;

  .orange_btn {
    color: $sugar-cane;
    background-color: $blaze-orange;
  }

  .secondary_btn {
    border-bottom: 2px solid rgba(160, 160, 160, 0.5);
    color: rgb(160, 160, 160);
  }

  h2 {
    font-weight: 400;
    color: $butterfly-bush;
  }

  .item_card {
    &_image {
      width: 60px;
      height: 60px;
      display: flex;
      justify-content: center;
      align-items: center;
      border-radius: 50%;
      background-color: $blaze-orange;
      img {
        width: 25px;
      }
    }
    &_text {
      h5 {
        font-weight: 400;
        color: $butterfly-bush;
      }
      small {
        color: $tuatara;
      }
    }
  }

  .primary_image {
    position: relative;
    .thumb {
      width: 40px;
      background-color: $blaze-orange;
      position: absolute;
      cursor: pointer;
    }
    .thumb_prev {
      bottom: 45%;
    }
    .thumb_next {
      bottom: 45%;
      right: 0;
    }
  }

  .selected {
    padding-bottom: 0.5rem;
    border-bottom: 3px solid $blaze-orange;
  }
}
</style>
