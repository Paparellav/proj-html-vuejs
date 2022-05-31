<template>
  <div class="section_5">
    <div class="container">
      <div class="row row-cols-2">
        <div class="col">
          <h2 class="mb-5">
            We have been educating children for <br />
            over fifteen years. Our goal is to create <br />
            a place that engages each child.
          </h2>
          <small
            >Praesent arcu gravida vehicula est node maecenas loareet morbi a
            <br />
            dosis luctus. Urna eget lacinia eleifend praesent luctus a arcu quis
            <br />
            facillisis aenean interdum.</small
          >
          <ul>
            <li>
              <span>&check;</span>Comprehensive reporting on individual
              achievement
            </li>
            <li>
              <span>&check;</span>Educational field trips and school
              presentations
            </li>
            <li>
              <span>&check;</span>Individual attention in a small-class setting
            </li>
            <li><span>&check;</span>Learning program with after-school care</li>
            <li>
              <span>&check;</span>Opportunities to carry our scientific
              investigations
            </li>
            <li>
              <span>&check;</span>Positive learning environment for your child
            </li>
          </ul>
        </div>
        <div class="col">
          <div class="row row-cols-2">
            <div class="col d-flex flex-column text-center mt-5">
              <div class="card-item">
                <img src="../assets/img/toy.png" alt="" />
              </div>
              <h6 class="mt-3">Learning & Fun</h6>
              <small class="mt-2">
                Praesent modea est gravida <br />node vehicula luctus.
              </small>
              <div class="card-item mt-5">
                <img src="../assets/img/school.png" alt="" />
              </div>
              <h6 class="mt-3">Friendly Place</h6>
              <small class="mt-2">
                Terminal interdum a eleifend <br />maecenas est morbi.
              </small>
            </div>
            <div class="col d-flex flex-column text-center mt-5">
              <div class="card-item">
                <img src="../assets/img/meal.png" alt="" />
              </div>
              <h6 class="mt-3">Healthy Meals</h6>
              <small class="mt-2">
                Terminal interdum a eleifend <br />maecenas est morbi.
              </small>
              <div class="card-item mt-5">
                <img src="../assets/img/shield.png" alt="" />
              </div>
              <h6 class="mt-3">Children Safety</h6>
              <small class="mt-2">
                Praesent modea est gravida <br />node vehicula luctus.
              </small>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppSectionFifth",
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";

.section_5 {
  padding: 3rem 0;
  background-color: $bon-jour;
  h2 {
    font-weight: 400;
    color: $victoria;
  }
  ul {
    padding: 0;
    margin-top: 2rem;
    li {
      margin-top: 1rem;
      display: flex;
      align-items: center;
      span {
        width: 25px;
        height: 25px;
        display: flex;
        justify-content: center;
        align-items: center;
        border: 3px solid $blaze-orange;
        margin-right: 0.5rem;
        font-weight: bold;
        color: $blaze-orange;
      }
    }
  }
  .card-item {
    width: 100px;
    height: 100px;
    margin: auto;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    background-color: $sugar-cane;
    img {
      width: 50px;
    }
  }
}
</style>
