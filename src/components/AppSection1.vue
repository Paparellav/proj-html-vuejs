<template>
  <div class="container">
    <div class="title_card text-center mt-5">
      <h2>Welcome to Fable</h2>
      <p>Fable daycare, preschool, and kindergarten</p>
      <img src="../assets/img/header_divider.png" alt="" />
    </div>
    <div class="items_card fluid-container mt-5">
      <div class="row row-cols-4">
        <div class="col d-flex flex-column text-center">
          <div class="orange-item">
            <img src="../assets/img/schoolbag_alt.png" alt="" />
          </div>
          <h6 class="mt-3">Morbi Etos</h6>
          <small class="mt-2">
            Praesent interdum est gravida<br />
            vehicula est node maecenas<br />
            loareet morbi a dosis luctus<br />
            novum est praesent.
          </small>
        </div>
        <div class="col d-flex flex-column text-center">
          <div class="purple-item">
            <img src="../assets/img/stroller_alt.png" alt="" />
          </div>
          <h6 class="mt-3">Congue Gravida</h6>
          <small class="mt-2">
            Ellipsis magna a terminal nulla <br />
            elementum morbi elite forte <br />
            maecenas est magna etos <br />
            interdum vitae est.
          </small>
        </div>
        <div class="col d-flex flex-column text-center">
          <div class="orange-item">
            <img src="../assets/img/globe_alt.png" alt="" />
          </div>
          <h6 class="mt-3">Maecenas Node</h6>
          <small class="mt-2">
            Praesent interdum est gravida<br />
            vehicula est node maecenas<br />
            loareet morbi a dosis luctus<br />
            novum est praesent.
          </small>
        </div>
        <div class="col d-flex flex-column text-center">
          <div class="purple-item">
            <img src="../assets/img/bell_alt.png" alt="" />
          </div>
          <h6 class="mt-3">Praesent Morbi</h6>
          <small class="mt-2">
            Ellipsis magna a terminal nulla <br />
            elementum morbi elite forte <br />
            maecenas est magna etos <br />
            interdum vitae est.
          </small>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppSectionOne",
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

.orange-item {
  width: 100px;
  height: 100px;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  background-color: $blaze-orange;
  img {
    width: 50px;
  }
}

.purple-item {
  width: 100px;
  height: 100px;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  background-color: $butterfly-bush;
  img {
    width: 50px;
  }
}

h6 {
  color: $victoria;
}
small {
  font-weight: lighter;
  color: $tuatara;
}
</style>
