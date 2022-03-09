<template>
  <section class="client_section layout_padding">
    <div class="container">
      <div class="heading_container heading_center">
        <h2>Customer's Testimonial</h2>
      </div>
      <div
        id="carouselExample3Controls"
        class="carousel slide"
        data-ride="carousel"
      >
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="box col-lg-10 mx-auto">
              <div class="img_container">
                <div class="img-box">
                  <div class="img_box-inner">
                    <img src="../assets/images/client.jpg" alt="" />
                  </div>
                </div>
              </div>
              <div class="detail-box">
                <h5>Anna Trevor</h5>
                <h6>Customer</h6>
                <p>
                  Dignissimos reprehenderit repellendus nobis error quibusdam?
                  Atque animi sint unde quis reprehenderit, et, perspiciatis,
                  debitis totam est deserunt eius officiis ipsum ducimus ad
                  labore modi voluptatibus accusantium sapiente nam! Quaerat.
                </p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="box col-lg-10 mx-auto">
              <div class="img_container">
                <div class="img-box">
                  <div class="img_box-inner">
                    <img src="../assets/images/client.jpg" alt="" />
                  </div>
                </div>
              </div>
              <div class="detail-box">
                <h5>Anna Trevor</h5>
                <h6>Customer</h6>
                <p>
                  Dignissimos reprehenderit repellendus nobis error quibusdam?
                  Atque animi sint unde quis reprehenderit, et, perspiciatis,
                  debitis totam est deserunt eius officiis ipsum ducimus ad
                  labore modi voluptatibus accusantium sapiente nam! Quaerat.
                </p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="box col-lg-10 mx-auto">
              <div class="img_container">
                <div class="img-box">
                  <div class="img_box-inner">
                    <img src="../assets/images/client.jpg" alt="" />
                  </div>
                </div>
              </div>
              <div class="detail-box">
                <h5>Anna Trevor</h5>
                <h6>Customer</h6>
                <p>
                  Dignissimos reprehenderit repellendus nobis error quibusdam?
                  Atque animi sint unde quis reprehenderit, et, perspiciatis,
                  debitis totam est deserunt eius officiis ipsum ducimus ad
                  labore modi voluptatibus accusantium sapiente nam! Quaerat.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel_btn_box">
          <a
            class="carousel-control-prev"
            href="#carouselExample3Controls"
            role="button"
            data-bs-slide="prev"
          >
            <i class="fa fa-long-arrow-left" aria-hidden="true"></i>
            <span class="sr-only">Previous</span>
          </a>
          <a
            class="carousel-control-next"
            href="#carouselExample3Controls"
            role="button"
            data-bs-slide="next"
          >
            <i class="fa fa-long-arrow-right" aria-hidden="true"></i>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
.layout_padding {
  padding: 70px 0;
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
.client_section .box {
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
  text-align: center;
  margin-top: 55px;
}

.client_section .box .img_container {
  width: auto;
  height: auto;
  border-radius: 100%;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: end;
  -ms-flex-pack: end;
  justify-content: flex-end;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: transparent;
}

.client_section .box .img_container .img-box {
  width: auto;
  height: auto;
  border-radius: 100%;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: #ffffff;
  margin-right: -1px;
}

.client_section .box .img_container .img-box .img_box-inner {
  width: 150px;
  height: 150px;
  border-radius: 100%;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  overflow: hidden;
}

.client_section .box .img_container .img-box .img_box-inner img {
  width: 100%;
}

.client_section .box .detail-box {
  margin-top: 25px;
}

.client_section .box .detail-box h5 {
  font-size: 20px;
  font-weight: 600;
}

.client_section .box .detail-box h6 {
  font-size: 15px;
  color: #999998;
}

.client_section .carousel-control-prev,
.client_section .carousel-control-next {
  top: 43%;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
  opacity: 1;
  width: auto;
  margin: 0 5px;
  width: 50px;
  height: 50px;
  opacity: 1;
  color: #ffffff;
  background-color: #f7444e;
  border-radius: 100%;
}

.client_section .carousel-control-prev:hover,
.client_section .carousel-control-next:hover {
  background-color: #212121;
}

.client_section .carousel-control-prev {
  left: 25%;
}

.client_section .carousel-control-next {
  right: 25%;
}

@media (max-width: 992px) {
  .client_section .carousel-control-prev {
    left: 15%;
  }

  .client_section .carousel-control-next {
    right: 15%;
  }
}

@media (max-width: 767px) {
  .client_section .carousel-control-prev {
    left: 5%;
  }

  .client_section .carousel-control-next {
    right: 5%;
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
  .carousel_btn_box {
    display: flex;
    justify-content: center;
    margin-top: 25px;
  }
  .client_section .carousel-control-prev,
  .client_section .carousel-control-next {
    position: unset;
    transform: none;
  }
}
</style>
