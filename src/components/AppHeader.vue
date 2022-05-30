<template>
  <header class="header">
    <div class="container">
      <div class="row">
        <div class="col-3">
          <div class="header__logo">
            <img src="../assets/img/logo.png" alt="logo-fable" />
          </div>
        </div>
        <div class="col-9">
          <nav class="header__nav">
            <ul>
              <li
                v-for="(item, index) in navArray"
                :key="index"
                :class="navArray[index].active ? 'active' : ''"
              >
                <a
                  href="#"
                  :class="navArray[index].active ? 'active-title' : ''"
                >
                  <img
                    :src="require(`../assets/img/${navArray[index].image}`)"
                    alt=""
                  />
                  <h5>{{ navArray[index].title }}</h5>
                </a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
  props: {
    navArray: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/variables.scss";

.header {
  background-color: $sugar-cane;
  &__logo {
    img {
      width: 170px;
    }
  }

  &__nav {
    height: 100%;
    display: flex;
    justify-content: center;
    ul {
      width: 100%;
      height: 100%;
      display: flex;
      justify-content: space-evenly;
      padding: 0;

      li {
        padding: 1rem;
        a {
          padding: 0 0.7rem;
          display: flex;
          flex-direction: column;
          align-items: center;
          color: $butterfly-bush;

          img {
            width: 25px;
            margin-bottom: 0.6rem;
          }

          h5 {
            font-weight: lighter;
          }
        }
      }

      .active {
        background-color: $blaze-orange;
      }

      .active-title {
        color: $sugar-cane;
      }
    }
  }
}
</style>
