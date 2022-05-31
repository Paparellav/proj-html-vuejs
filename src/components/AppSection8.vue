<template>
  <div class="container">
    <div class="title_card text-center mt-5">
      <h2>What's New</h2>
      <p>Keep up to date with the latest news</p>
      <img src="../assets/img/header_divider.png" alt="" />
    </div>
    <div class="row row-cols-3 mt-5">
      <div class="col">
        <!-- Item card -->
        <div class="item_card">
          <small>October 03, 2014</small>
          <div class="item_card_image">
            <img src="../assets/img/blog_09.jpg" alt="" />
            <div class="pic_number">42</div>
          </div>
          <h4>Drawing and Painting Lessons</h4>
          <p>
            Magna est consecteur interdum modest <br />dictum. Curabitur est
            faucibus, malesuada <br />esttincidunt etos et mauris, nunc a libero
            <br />govum est cuprum <span>[...]</span>
          </p>
          <div class="contacts d-flex">
            <div class="contacts_btn">
              <img src="../assets/img/author.png" alt="" />
              <small>Anna Brown</small>
            </div>
            <div class="contacts_btn ms-4">
              <img src="../assets/img/category.png" alt="" />
              <small>Events, Fun</small>
            </div>
          </div>
        </div>
        <!-- Item card -->
      </div>
      <div class="col">
        <!-- Item card -->
        <div class="item_card">
          <small>October 03, 2014</small>
          <div class="item_card_image">
            <img src="../assets/img/blog_10.jpg" alt="" />
            <div class="pic_number">19</div>
          </div>
          <h4>Fall Parents Meeting Day</h4>
          <p>
            Magna est consecteur interdum modest <br />dictum. Curabitur est
            faucibus, malesuada <br />esttincidunt etos et mauris, nunc a libero
            <br />govum est cuprum <span>[...]</span>
          </p>
          <div class="contacts d-flex">
            <div class="contacts_btn">
              <img src="../assets/img/author.png" alt="" />
              <small>Anna Brown</small>
            </div>
            <div class="contacts_btn ms-4">
              <img src="../assets/img/category.png" alt="" />
              <small>Dance, Education</small>
            </div>
          </div>
        </div>
        <!-- Item card -->
      </div>
      <div class="col">
        <!-- Item card -->
        <div class="item_card">
          <small>September 20, 2014</small>
          <div class="item_card_image">
            <img src="../assets/img/blog_08.jpg" alt="" />
            <div class="pic_number">22</div>
          </div>
          <h4>Birthday in Kindergarten</h4>
          <p>
            Magna est consecteur interdum modest <br />dictum. Curabitur est
            faucibus, malesuada <br />esttincidunt etos et mauris, nunc a libero
            <br />govum est cuprum <span>[...]</span>
          </p>
          <div class="contacts d-flex">
            <div class="contacts_btn">
              <img src="../assets/img/author.png" alt="" />
              <small>Anna Brown</small>
            </div>
            <div class="contacts_btn ms-4">
              <img src="../assets/img/category.png" alt="" />
              <small>Games, General</small>
            </div>
          </div>
        </div>
        <!-- Item card -->
      </div>
    </div>
    <div class="border_btn">
      <button class="btn ms_btn">Go to blog</button>
      <img src="../assets/img/slider_next.png" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: "AppSection8",
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

.item_card {
  small {
    color: rgb(182, 182, 182);
  }
  &_image {
    margin-top: 1rem;
    position: relative;
    .pic_number {
      padding: 0.5rem 0.7rem;
      color: $sugar-cane;
      background-color: $blaze-orange;
      position: absolute;
      bottom: 0;
      right: 0;
    }
  }
  h4 {
    margin: 1rem 0;
    font-weight: 400;
    color: $butterfly-bush;
  }
  p {
    color: $tuatara;
    padding-bottom: 1.5rem;
    border-bottom: 1px solid rgb(230, 230, 230);
  }
  span {
    color: rgb(182, 182, 182);
  }
  .contacts_btn {
    display: flex;
    justify-content: space-between;
    align-items: center;
    img {
      width: 20px;
      margin-right: 0.5rem;
    }
  }
}
.border_btn {
  width: 170px;
  height: 50px;
  margin: 4rem auto;
  display: flex;
  justify-content: center;
  align-items: center;
  align-self: center;
  background-color: $blaze-orange;
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
</style>
