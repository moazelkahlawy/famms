<template>
  <section class="hero_area">
    <div id="customCarousel1" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div class="container">
            <div class="row">
              <div class="col-md-7 col-lg-6">
                <div class="detail-box">
                  <h1>
                    <span> Sale 20% Off </span>
                    <br />
                    On Everything
                  </h1>
                  <p>
                    Explicabo esse amet tempora quibusdam laudantium, laborum
                    eaque magnam fugiat hic? Esse dicta aliquid error
                    repudiandae earum suscipit fugiat molestias, veniam, vel
                    architecto veritatis delectus repellat modi impedit sequi.
                  </p>
                  <div class="btn-box">
                    <a href="" class="btn1"> Shop Now </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="container">
            <div class="row">
              <div class="col-md-7 col-lg-6">
                <div class="detail-box">
                  <h1>
                    <span> Sale 20% Off </span>
                    <br />
                    On Everything
                  </h1>
                  <p>
                    Explicabo esse amet tempora quibusdam laudantium, laborum
                    eaque magnam fugiat hic? Esse dicta aliquid error
                    repudiandae earum suscipit fugiat molestias, veniam, vel
                    architecto veritatis delectus repellat modi impedit sequi.
                  </p>
                  <div class="btn-box">
                    <a href="" class="btn1"> Shop Now </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="container">
            <div class="row">
              <div class="col-md-7 col-lg-6">
                <div class="detail-box">
                  <h1>
                    <span> Sale 20% Off </span>
                    <br />
                    On Everything
                  </h1>
                  <p>
                    Explicabo esse amet tempora quibusdam laudantium, laborum
                    eaque magnam fugiat hic? Esse dicta aliquid error
                    repudiandae earum suscipit fugiat molestias, veniam, vel
                    architecto veritatis delectus repellat modi impedit sequi.
                  </p>
                  <div class="btn-box">
                    <a href="" class="btn1"> Shop Now </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="container">
        <ol class="carousel-indicators">
          <li
            data-bs-target="#customCarousel1"
            data-bs-slide-to="0"
            class="active"
          ></li>
          <li data-bs-target="#customCarousel1" data-bs-slide-to="1"></li>
          <li data-bs-target="#customCarousel1" data-bs-slide-to="2"></li>
        </ol>
      </div>
    </div>
  </section>
  <TheWhy />
  <TheArrival />
  <TheProduct />
  <section class="subscribe_section">
    <div class="container-fuild">
      <div class="box">
        <div class="row">
          <div class="col-md-6 offset-md-3">
            <div class="subscribe_form">
              <div class="heading_container heading_center">
                <h3>Subscribe To Get Discount Offers</h3>
              </div>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor
              </p>
              <form action="">
                <input type="email" placeholder="Enter your email" />
                <button>subscribe</button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <TheClient />
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="full">
            <div class="logo_footer">
              <a href="#"><img width="210" src="../assets/images/logo.png" alt="#" /></a>
            </div>
            <div class="information_f">
              <p>
                <strong>ADDRESS:</strong> 28 White tower, Street Name New York
                City, USA
              </p>
              <p><strong>TELEPHONE:</strong> +91 987 654 3210</p>
              <p><strong>EMAIL:</strong> yourmain@gmail.com</p>
            </div>
          </div>
        </div>
        <div class="col-md-8">
          <div class="row">
            <div class="col-md-7">
              <div class="row">
                <div class="col-md-6">
                  <div class="widget_menu">
                    <h3>Menu</h3>
                    <ul>
                      <li><a href="#">Home</a></li>
                      <li><a href="#">About</a></li>
                      <li><a href="#">Services</a></li>
                      <li><a href="#">Testimonial</a></li>
                      <li><a href="#">Blog</a></li>
                      <li><a href="#">Contact</a></li>
                    </ul>
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="widget_menu">
                    <h3>Account</h3>
                    <ul>
                      <li><a href="#">Account</a></li>
                      <li><a href="#">Checkout</a></li>
                      <li><a href="#">Login</a></li>
                      <li><a href="#">Register</a></li>
                      <li><a href="#">Shopping</a></li>
                      <li><a href="#">Widget</a></li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-5">
              <div class="widget_menu">
                <h3>Newsletter</h3>
                <div class="information_f">
                  <p>Subscribe by our newsletter and get update protidin.</p>
                </div>
                <div class="form_sub">
                  <form>
                    <fieldset>
                      <div class="field">
                        <input
                          type="email"
                          placeholder="Enter Your Mail"
                          name="email"
                        />
                        <input type="submit" value="Subscribe" />
                      </div>
                    </fieldset>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
  <div class="cpy_">
    <p>© 2022 All Rights Reserved</p>
  </div>
</template>

<script>
import TheWhy from "@/components/TheWhy.vue";
import TheArrival from "@/components/TheArrival.vue";
import TheProduct from "@/components/TheProduct.vue";
import TheClient from "@/components/TheClient.vue";
export default {
  name: "HomeView",
  components: {
    TheWhy,
    TheArrival,
    TheProduct,
    TheClient,
  },
};
</script>

<style scoped>
.hero_area {
  height: calc(100vh - 84px);
  background-image: url("../assets/images/slider-bg.jpg");
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;
}

.hero_area {
  -webkit-box-flex: 1;
  -ms-flex: 1;
  flex: 1;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  position: relative;
  padding: 90px 0 75px 0;
}

.hero_area .row {
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

.hero_area #customCarousel1 {
  width: 100%;
  position: unset;
}

.hero_area .detail-box h1 {
  font-size: 4.5rem;
  font-weight: bold;
  margin-bottom: 15px;
  color: #002c3e;
  line-height: 70px;
}

.hero_area .detail-box h1 span {
  color: #f7444e;
}

.hero_area .detail-box p {
  font-size: 16px;
  margin-top: 20px;
  margin-bottom: 1.5rem;
}

.hero_area .detail-box a {
  display: inline-block;
  padding: 12px 45px;
  background-color: #f7444e;
  border: 1px solid #f7444e;
  color: #ffffff;
  border-radius: 0;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  margin-top: 10px;
  font-weight: 700;
}

.hero_area .detail-box a:hover {
  background-color: transparent;
  color: #f7444e;
}

.hero_area .img-box img {
  width: 100%;
}

.hero_area .carousel-indicators {
  position: unset;
  margin: 0;
  margin-top: 45px;
  -webkit-box-pack: start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

.hero_area .carousel-indicators li {
  background-color: #ffffff;
  width: 12px;
  height: 12px;
  border-radius: 100%;
  opacity: 1;
}

.hero_area .carousel-indicators li.active {
  width: 20px;
  height: 20px;
  background-color: #f7444e;
}

.heading_container.heading_center h3 {
  position: relative;
  margin-bottom: 15px;
  font-size: 2.5rem;
  font-weight: bold;
  font-family: "Playfair Display", serif;
}

.heading_container {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: start;
  -ms-flex-align: start;
  align-items: flex-start;
}

.heading_container h2 {
  position: relative;
  margin-bottom: 0;
  font-size: 3.5rem;
  font-weight: bold;
}

.heading_container h2::after {
  content: "";
  display: block;
  width: 70px;
  height: 5px;
  background: #f7444e;
  margin: 10px auto 10px;
}

.heading_container h2 span {
  color: #f7444e;
}

.heading_container p {
  margin-top: 10px;
  margin-bottom: 0;
}

.heading_container.heading_center {
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  text-align: center;
}
.subscribe_section {
  text-align: center;
}

.subscribe_section .box {
  background-color: #d4ced0;
  padding: 75px 45px;
}

.subscribe_section .subscribe_form .heading_container {
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  color: #002c3e;
}

.subscribe_section .subscribe_form .heading_container h2 {
  padding: 0 25px;
}

.subscribe_section .subscribe_form form {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

.subscribe_section .subscribe_form form input {
  width: 100%;
  height: 60px;
  border: none;
  border-radius: 90px;
  outline: none;
  padding: 5px 25px;
  background-color: #ffffff;
  margin-top: 15px;
  text-align: left;
}

.subscribe_section .subscribe_form form input::-webkit-input-placeholder {
  color: #171620;
}

.subscribe_section .subscribe_form form input:-ms-input-placeholder {
  color: #171620;
}

.subscribe_section .subscribe_form form input::-ms-input-placeholder {
  color: #171620;
}

.subscribe_section .subscribe_form form input::placeholder {
  color: #171620;
}

.subscribe_section .subscribe_form form button {
  display: inline-block;
  padding: 10px 45px;
  background-color: #f7444e;
  border: 1px solid #f7444e;
  color: #ffffff;
  border-radius: 35px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  text-transform: uppercase;
  margin-top: 35px;
  font-weight: 600;
  width: 100%;
  max-width: 285px;
}

.subscribe_section .subscribe_form form button:hover {
  background-color: transparent;
  color: #f7444e;
}

footer {
  background: #f8f8f8;
  padding: 90px 0 70px;
}

.logo_footer {
  margin-bottom: 30px;
}

.information_f p {
  margin-bottom: 1.2rem;
  line-height: 25px;
  font-size: 15px;
}

.widget_menu h3 {
  font-size: 18px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.2px;
  margin-bottom: 25px;
}

.widget_menu ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.widget_menu ul li {
  float: left;
  width: 100%;
}

.widget_menu ul li a {
  font-size: 15px;
  color: #000;
  margin-bottom: 0;
  float: left;
  width: 100%;
  margin-top: 5px;
}

.field {
  display: flex;
}

.widget_menu {
  float: left;
  width: 100%;
}

div.form_sub .field input[type="email"],
div.form_sub .field input[type="email"]:hover,
div.form_sub .field input[type="email"]:focus {
  padding: 10px 110px 10px 15px;
  border-radius: 0;
  border: solid #ccc 1px;
  font-size: 14px;
  position: relative;
  box-shadow: none;
  width: 100%;
  height: 48px;
}

.form_sub {
  position: relative;
}

.form_sub input[type="email"] + input[type="submit"] {
  position: absolute;
  right: 0;
  background: #f7444e;
  color: #fff;
  border: none;
  top: 0px;
  font-size: 14px;
  height: 48px;
  font-weight: 600;
  padding: 0 15px;
}

form input {
  background: #fff;
  border: solid #ccc 1px;
  padding: 15px 15px;
  width: 100%;
  font-size: 14px;
  margin-bottom: 20px;
  text-transform: capitalize;
  line-height: normal;
}

form textarea {
  background: #fff;
  border: solid #ccc 1px;
  padding: 15px 15px;
  width: 100%;
  min-height: 150px;
  font-size: 14px;
  margin-bottom: 20px;
  text-transform: capitalize;
  line-height: normal;
}

form input[type="submit"] {
  border: none;
  padding: 15px 45px;
  width: auto;
  font-size: 16px;
  text-transform: capitalize;
  line-height: normal;
  margin: 0 auto;
  display: flex;
  background: #333;
  color: #fff;
  font-weight: 600;
  transition: ease all 0.1s;
}

form input[type="submit"]:hover,
form input[type="submit"]:focus {
  background: #f7444e;
  color: #fff;
}

.cpy_ {
  background: #222;
  text-align: center;
  padding: 20px 0;
}

.cpy_ p {
  margin: 0;
  color: #fff;
  font-size: 15px;
  font-weight: 400;
}

.cpy_ p a {
  margin: 0;
  color: #f7444e;
  font-size: 15px;
  font-weight: 400;
}

@media (max-width: 992px) {
  .hero_area .carousel-indicators {
    margin-top: -23px;
  }
}

@media (max-width: 768px) {
  .hero_area .detail-box {
    margin-bottom: 45px;
  }
  
  .hero_area .carousel-indicators {
    margin-top: -10px;
  }
}

@media (max-width: 576px) {
  .heading_container h2 {
    font-size: 2.2rem;
  }
}

@media (max-width: 480px) {
  .heading_container h2 {
    font-size: 2rem;
  }
}

@media (max-width: 376px) {
  .hero_area .detail-box h1 {
    font-size: 3rem;
  }
}
</style>
