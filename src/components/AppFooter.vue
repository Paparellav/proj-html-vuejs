<template>
  <footer>
    <div class="footer_top">
      <div class="container">
        <div class="row row-cols-4">
          <!-- Primera col -->
          <div class="col d-flex flex-column">
            <h3 class="text-uppercase">About us</h3>
            <div class="grey_band mb-5"></div>
            <p>
              Ellipsis magna a nulla elite forte maecenas est elementum magna
              etos interdum movum morbi vehicula morbi.
            </p>
            <div class="logo_footer pt-3">
              <img src="../assets/img/logo_footer.png" alt="" />
            </div>
          </div>
          <!-- Primera col -->
          <!-- Segunda col -->
          <div class="col d-flex flex-column">
            <h3 class="text-uppercase">Archives</h3>
            <div class="grey_band mb-5"></div>
            <div
              v-for="(item, index) in archives"
              :key="index"
              class="archives_card text-uppercase"
            >
              {{ item.month + " " + item.year + " " + item.documents }}
            </div>
          </div>
          <!-- Segunda col -->
          <!-- Terceira col -->
          <div class="col d-flex flex-column">
            <h3 class="text-uppercase">Our features</h3>
            <div class="grey_band mb-5"></div>
            <p>
              Nunc gravida retrum mauris vehin hasellus ac pretium augue vivamul
              lacus ligul mattis ac vene:
            </p>
            <ul>
              <li
                v-for="(item, index) in features"
                :key="'A' + index"
                class="features_card"
              >
                <img :src="require(`../assets/img/${item.image}`)" alt="" />
                <p>{{ item.feature }}</p>
              </li>
            </ul>
          </div>
          <!-- Terceira col -->
          <!-- Quarta col -->
          <div class="col d-flex flex-column">
            <h3 class="text-uppercase">Recent posts</h3>
            <div class="grey_band mb-5"></div>
            <div
              v-for="(item, index) in posts"
              :key="'B' + index"
              class="item_card d-flex mb-4"
            >
              <div class="item_card_image">
                <img :src="require(`../assets/img/${item.postImage}`)" alt="" />
              </div>
              <div class="item_card_text ps-3">
                <h5>{{ item.title }}</h5>
                <div class="date">
                  <img :src="require(`../assets/img/${item.dateImg}`)" alt="" />
                  <small>{{ item.dateTxt }}</small>
                </div>
              </div>
            </div>
          </div>
          <!-- Quarta col -->
        </div>
      </div>
    </div>
    <div class="footer_bottom text-center">
      <div class="socials pb-3">
        <div
          v-for="(item, index) in socials"
          :key="'C' + index"
          class="socials_card"
        >
          <img :src="require(`../assets/img/${item}`)" alt="" />
        </div>
      </div>
      <p>
        &copy; Fable ~ Children Kindergarten WordPress Theme by QuanticaLabs
      </p>
      <div class="footer_chevron">
        <img src="../assets/img/go_to_top.png" alt="" />
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "AppFooter",
  props: {
    archives: Array,
    features: Array,
    posts: Array,
    socials: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";

.footer_top {
  padding: 6rem 0;
  color: $bon-jour;
  background-image: url("../assets/img/pattern.png");
  .grey_band {
    width: 80px;
    height: 2px;
    margin: 1rem 0;
    background-color: $bon-jour;
  }
  .archives_card {
    border: 1px solid $bon-jour;
    padding: 1rem;
    margin: 0.3rem 0;
  }
  ul {
    margin-top: 1.5rem;
    padding: 0;
    .features_card {
      img {
        width: 20px;
        vertical-align: middle;
      }
      p {
        display: inline-block;
        margin-left: 0.7rem;
      }
    }
  }
  .item_card_image {
    img {
      width: 110px;
    }
  }
  .date {
    padding-top: 1.2rem;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    img {
      width: 20px;
    }
    small {
      margin-left: 1.2rem;
    }
  }
}
.footer_bottom {
  padding: 1rem 0;
  color: $tuatara;
  position: relative;
  .socials {
    display: flex;
    justify-content: center;
    &_card {
      margin-right: 0.2rem;
      background-color: $blaze-orange;
      img {
        width: 50px;
      }
    }
  }
  p {
    color: rgb(174, 174, 174);
  }
  .footer_chevron {
    width: 50px;
    background-color: rgb(199, 199, 199);
    position: absolute;
    bottom: 5%;
    right: 0.3%;
    img {
      width: 50px;
    }
  }
}
</style>
