<template>
  <div class="container">
    <div class="title_card text-center mt-5 mb-5">
      <h2>Meet Our Staff</h2>
      <p>With education and experience in early childhood care</p>
      <img src="../assets/img/header_divider.png" alt="" />
    </div>
    <div class="row row-cols-2">
      <div class="col">
        <h2>
          Our staff consists oh three teachers <br />
          and one assistant with experience in <br />
          early childhood care.
        </h2>
        <!-- Iniziano gli item card -->
        <div class="item_card d-flex mt-5">
          <div class="left_col d-flex flex-column text-center">
            <div class="item_card_image">
              <img src="../assets/img/team_04.jpg" alt="" />
            </div>
            <h5>Ruth Richie</h5>
            <small>Teacher</small>
          </div>
          <div class="right_col">
            <div class="quote_card">
              <img src="../assets/img/quote.png" alt="" />
            </div>
            <p>
              I have just finished my studies in Early Childhood Education, and
              I am also the kid's yoga teacher here at Fable. I enjoy cooking,
              swimming and bike riding in my free time.
            </p>
            <div class="socials d-flex">
              <div class="socials_card">
                <img src="../assets/img/mail.png" alt="" />
              </div>
              <div class="socials_card">
                <img src="../assets/img/facebook.png" alt="" />
              </div>
              <div class="socials_card">
                <img src="../assets/img/pinterest.png" alt="" />
              </div>
            </div>
          </div>
        </div>
        <!-- Iniziano gli item card -->
        <!-- Iniziano gli item card -->
        <div class="item_card d-flex mt-5">
          <div class="left_col d-flex flex-column text-center">
            <div class="item_card_image">
              <img src="../assets/img/team_02.jpg" alt="" />
            </div>
            <h5>Angelica Watson</h5>
            <small>Lead Teacher</small>
          </div>
          <div class="right_col">
            <div class="quote_card">
              <img src="../assets/img/quote.png" alt="" />
            </div>
            <p>
              I hold a degree in Early Childhood Education and an advanced
              English language certificate. I have been working as a
              kindergarten teacher since 2002.
            </p>
            <div class="socials_low d-flex">
              <div class="socials_low_card">
                <img src="../assets/img/bing.png" alt="" />
              </div>
              <div class="socials_low_card">
                <img src="../assets/img/skype.png" alt="" />
              </div>
              <div class="socials_low_card">
                <img src="../assets/img/linkedin.png" alt="" />
              </div>
            </div>
          </div>
        </div>
        <!-- Iniziano gli item card -->
      </div>
      <div class="col">
        <h5 class="subtitle">
          Praesent arcu gravida vehicula est node maecenas loareet morbi a
          <br />
          dosis luctus. Urna eget lacinia eleifend praesent luctus a arcu quis
          <br />facillisis venenatis. Aenean interdum, nibh vitae sodales, magna
          ante <br />feugiat elit maecenas.
        </h5>
        <!-- Iniziano gli item card -->
        <div class="item_card right_m d-flex">
          <div class="left_col d-flex flex-column text-center">
            <div class="item_card_image">
              <img src="../assets/img/team_03.jpg" alt="" />
            </div>
            <h5>Katie Willmore</h5>
            <small>Assistant Teacher</small>
          </div>
          <div class="right_col">
            <div class="quote_card">
              <img src="../assets/img/quote.png" alt="" />
            </div>
            <p>
              My name is Katie. I grew up and studied in Canada. This is my
              second year at Fable and love every minute of it, making the
              children's learning experience fun.
            </p>
            <div class="socials_low d-flex">
              <div class="socials_low_card">
                <img src="../assets/img/dribbble.png" alt="" />
              </div>
              <div class="socials_low_card">
                <img src="../assets/img/stumbleupon.png" alt="" />
              </div>
              <div class="socials_low_card">
                <img src="../assets/img/instagram.png" alt="" />
              </div>
            </div>
          </div>
        </div>
        <!-- Iniziano gli item card -->
        <!-- Iniziano gli item card -->
        <div class="item_card d-flex mt-5">
          <div class="left_col d-flex flex-column text-center">
            <div class="item_card_image">
              <img src="../assets/img/team_01.jpg" alt="" />
            </div>
            <h5>Angela Lynn</h5>
            <small>Teacher</small>
          </div>
          <div class="right_col">
            <div class="quote_card">
              <img src="../assets/img/quote.png" alt="" />
            </div>
            <p>
              I have completed a Graduate Diploma in Early Childhood Teaching. I
              have worked with children aged from six weeks to eight years. This
              is my second year at Fable.
            </p>
            <div class="socials_low d-flex">
              <div class="socials_low_card">
                <img src="../assets/img/youtube.png" alt="" />
              </div>
              <div class="socials_low_card">
                <img src="../assets/img/twitter.png" alt="" />
              </div>
              <div class="socials_low_card">
                <img src="../assets/img/googleplus.png" alt="" />
              </div>
            </div>
          </div>
        </div>
        <!-- Iniziano gli item card -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppSectionSixth",
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

.right_m {
  margin-top: 4rem;
}

h2 {
  font-weight: 400;
  color: $victoria;
}

h5.subtitle {
  font-weight: lighter;
  color: $tuatara;
}

.left_col {
  h5 {
    margin-top: 1rem;
    color: $victoria;
  }
  small {
    color: grey;
  }
}

.item_card_image {
  img {
    width: 300px;
  }
}

.right_col {
  position: relative;

  .quote_card {
    width: 120px;
    height: 55px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
    border: 3px solid $blaze-orange;
    position: absolute;
    top: 10%;
    left: -10%;
    img {
      width: 35px;
      margin-right: 0.5rem;
    }
  }
  p {
    margin-top: 10rem;
    margin-left: 2rem;
  }
  .socials {
    margin-top: 3rem;
    margin-left: 2rem;
    &_card {
      margin-right: 0.2rem;
      background-color: $blaze-orange;
    }
  }
  .socials_low {
    margin-top: 5rem;
    margin-left: 2rem;
    &_card {
      margin-right: 0.2rem;
      background-color: $blaze-orange;
    }
  }
}
</style>
