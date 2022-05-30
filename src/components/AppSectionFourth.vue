<template>
  <div>
    <div class="title_card text-center mt-5 mb-5">
      <h2>Our Classes</h2>
      <p>Our preschool program has four dedicated classes</p>
      <img src="../assets/img/header_divider.png" alt="" />
    </div>
    <div class="container">
      <div class="row row-cols 2">
        <div class="col">
          <h2>
            We provided four classes with nine to <br />
            twenty children each aged twelve <br />
            month to five years of age.
          </h2>
          <div class="item_card_4">
            <div class="row row-cols-2 g-0">
              <div class="col mt-5">
                <div class="purple_col_area">
                  <h4>Little Lambs</h4>
                  <h5 class="mb-5">Class name</h5>
                  <div
                    class="fluid-container d-flex text-center justify-content-center"
                  >
                    <div class="left_footer_card me-3">
                      <div>12-24</div>
                      <small>Months olds</small>
                    </div>
                    <div class="right_footer_card">
                      <div>9</div>
                      <small>Class size</small>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col mt-5">
                <div class="item_image_4">
                  <img src="../assets/img/gallery_04-690x506.jpg" alt="" />
                  <button class="mt-4 me-4 btn orange_btn">Read More</button>
                </div>
              </div>
            </div>
          </div>
          <div class="item_card_4">
            <div class="row row-cols-2 g-0">
              <div class="col mt-5">
                <div class="purple_col_area">
                  <h4>Tenderhearts</h4>
                  <h5 class="mb-5">Class name</h5>
                  <div
                    class="fluid-container d-flex text-center justify-content-center"
                  >
                    <div class="left_footer_card me-3">
                      <div>3-4</div>
                      <small>Years olds</small>
                    </div>
                    <div class="right_footer_card">
                      <div>15</div>
                      <small>Class size</small>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col mt-5">
                <div class="item_image_4">
                  <img src="../assets/img/class_03-690x506.jpg" alt="" />
                  <button class="mt-4 me-4 btn orange_btn">Read More</button>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <h2 class="subtitle">
            We provided four classes with nine to <br />
            twenty children each aged twelve <br />
            month to five years of age.
          </h2>
          <div class="item_card_4">
            <div class="row row-cols-2 g-0">
              <div class="col mt-5">
                <div class="purple_col_area">
                  <h4>Bouncy Bears</h4>
                  <h5 class="mb-5">Class name</h5>
                  <div
                    class="fluid-container d-flex text-center justify-content-center"
                  >
                    <div class="left_footer_card me-3">
                      <div>2-3</div>
                      <small>Years olds</small>
                    </div>
                    <div class="right_footer_card">
                      <div>12</div>
                      <small>Class size</small>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col mt-5">
                <div class="item_image_4">
                  <img src="../assets/img/class_02-690x506.jpg" alt="" />
                  <button class="mt-4 me-4 btn orange_btn">Read More</button>
                </div>
              </div>
            </div>
          </div>
          <div class="item_card_4">
            <div class="row row-cols-2 g-0">
              <div class="col mt-5">
                <div class="purple_col_area">
                  <h4>Shining Stars</h4>
                  <h5 class="mb-5">Class name</h5>
                  <div
                    class="fluid-container d-flex text-center justify-content-center"
                  >
                    <div class="left_footer_card me-3">
                      <div>4-5</div>
                      <small>Years olds</small>
                    </div>
                    <div class="right_footer_card">
                      <div>20</div>
                      <small>Class size</small>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col mt-5">
                <div class="item_image_4">
                  <img src="../assets/img/class_04-690x506.jpg" alt="" />
                  <button class="mt-4 me-4 btn orange_btn">Read More</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppSectionFourth",
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";

.title_card {
  h2 {
    font-weight: lighter;
    color: $victoria;
  }

  p {
    font-weight: lighter;
    color: $tuatara;
  }

  img {
    width: 100px;
  }
}

h2 {
  font-weight: 400;
  color: $victoria;
}

h2.subtitle {
  font-weight: lighter;
  color: $tuatara;
}

.purple_col_area {
  height: 220px;
  padding: 2rem 1rem;
  background-color: $butterfly-bush;
  color: $sugar-cane;
  h5 {
    font-weight: 400;
  }

  .left_footer_card {
    border-right: 2px solid grey;
    padding-right: 1rem;
  }
}

.item_image_4 {
  position: relative;
  img {
    height: 220px;
  }
}

.orange_btn {
  border-radius: 0;
  color: $sugar-cane;
  background-color: $blaze-orange;
  position: absolute;
  bottom: 0;
  right: -24px;
}
</style>
