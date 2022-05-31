<template>
  <div class="banner_section_7">
    <div class="container text-center">
      <div class="quote_card">
        <img src="../assets/img/quote_alt.png" alt="" />
      </div>
      <h1>
        Fable Kindergarten is a great place for my daughter to start her
        <br />schooling experience. It's welcoming and safe and my daughter
        <br />loves being there.
      </h1>
      <div class="grey_band"></div>
      <h4>Joe R. Hamblen</h4>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppSection7",
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";

.banner_section_7 {
  padding: 7rem 0;
  background-image: url("../assets/img/parallax_02.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  filter: grayscale(0.5);
  color: $sugar-cane;

  .quote_card {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 3px solid $sugar-cane;
    margin: auto;

    img {
      width: 50px;
    }
  }

  h1 {
    margin-top: 2rem;
    font-weight: lighter;
  }

  .grey_band {
    width: 150px;
    height: 5px;
    margin: 3rem auto;
    background-color: $sugar-cane;
  }

  h4 {
    font-weight: 400;
  }
}
</style>
