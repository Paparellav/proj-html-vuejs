<template>
  <div class="container">
    <div class="title_card text-center mt-5">
      <h2>Contact Us</h2>
      <p>Our postal adress and contact details</p>
      <img src="../assets/img/header_divider.png" alt="" />
    </div>
    <div class="row row-cols-4 mt-5">
      <div class="col">
        <!-- Item card -->
        <div class="item_card d-flex flex-column text-center">
          <div class="item_card_image">
            <img src="../assets/img/envelope (1).png" alt="" />
          </div>
          <h3>Postal Adress</h3>
          <small>Fable Care Center</small>
          <small>85 Fentiman Ave</small>
          <small>Ottawa, ON K1S 0T7</small>
        </div>
        <!-- Item card -->
      </div>
      <div class="col">
        <!-- Item card -->
        <div class="item_card d-flex flex-column text-center">
          <div class="item_card_image">
            <img src="../assets/img/mobile.png" alt="" />
          </div>
          <h3>Phone & E-mail</h3>
          <small>Phone: 1-800-64-38</small>
          <small>Fax: 1-800-64-39</small>
          <small><a href="#">office@fable.com</a></small>
        </div>
        <!-- Item card -->
      </div>
      <div class="col">
        <!-- Item card -->
        <div class="item_card d-flex flex-column text-center">
          <div class="item_card_image">
            <img src="../assets/img/clock.png" alt="" />
          </div>
          <h3>Business Hours</h3>
          <small>Monday ~ Friday</small>
          <small>8.00 am ~ 5.00 pm</small>
          <small>Weekend Closed</small>
        </div>
        <!-- Item card -->
      </div>
      <div class="col">
        <!-- Item card -->
        <div class="item_card d-flex flex-column text-center">
          <div class="item_card_image">
            <img src="../assets/img/document (1).png" alt="" />
          </div>
          <h3>Sessions</h3>
          <small>Mornings, 8 am ~ 12 noon</small>
          <small>Afternoons, 1 pm ~ 5 pm</small>
          <small>Full Day, 8 am ~ 5 pm</small>
        </div>
        <!-- Item card -->
      </div>
    </div>
    <div class="row row-cols-2 mt-5">
      <div class="col d-flex flex-column">
        <div class="first_input">
          <input type="text" name="name" id="name" placeholder="Your Name *" />
          <img class="input_image" src="../assets/img/image.png" alt="" />
        </div>
        <input
          type="email"
          name="email"
          id="email"
          placeholder="Your E-mail *"
        />
        <input type="text" name="subject" id="subject" placeholder="Subject" />
      </div>
      <div class="col">
        <textarea
          name="textarea"
          id="textarea"
          placeholder="Your Message *"
        ></textarea>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppSection10",
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
  &_image {
    img {
      width: 50px;
    }
  }
  h3 {
    margin-top: 1.5rem;
    font-weight: 400;
    color: $butterfly-bush;
  }
  small {
    margin: 0.3rem 0;
    color: $tuatara;
    a {
      text-decoration: underline;
    }
  }
}

input {
  width: 100%;
  margin: 1rem 0;
  padding: 0.7rem;
  border: 1px solid $bon-jour;
}

textarea {
  width: 100%;
  height: 87%;
  margin: 1rem 0;
  padding: 0.7rem;
  border: 1px solid $bon-jour;
}

.first_input {
  position: relative;
  .input_image {
    width: 20px;
    position: absolute;
    top: 40%;
    right: 2%;
  }
}
</style>
