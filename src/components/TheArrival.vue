<template>
  <section class="arrival_section">
    <div class="container">
      <div class="box">
        <div class="arrival_bg_box">
          <img src="../assets/images/arrival-bg.png" alt="" />
        </div>
        <div class="row">
          <div class="col-md-6 ms-auto">
            <div class="heading_container remove_line_bt">
              <h2>#NewArrivals</h2>
            </div>
            <p style="margin-top: 20px; margin-bottom: 30px">
              Vitae fugiat laboriosam officia perferendis provident aliquid
              voluptatibus dolorem, fugit ullam sit earum id eaque nisi hic?
              Tenetur commodi, nisi rem vel, ea eaque ab ipsa, autem similique
              ex unde!
            </p>
            <a href="/"> Shop Now </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
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
.arrival_section {
  background-color: #d4ced0;
}
.arrival_section .heading_container {
  color: #002c3e;
  margin-bottom: 10px;
}

.arrival_section .box {
  padding: 120px 45px;
  position: relative;
}

.arrival_section .arrival_bg_box {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 3;
}

.arrival_section .arrival_bg_box img {
  width: 50%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
  -o-object-position: top left;
  object-position: top left;
}

.arrival_section a {
  display: inline-block;
  padding: 10px 45px;
  background-color: #f7444e;
  border: 1px solid #f7444e;
  color: #ffffff;
  border-radius: 0;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

.arrival_section a:hover {
  background-color: transparent;
  color: #f7444e;
}

.remove_line_bt h2::after {
  display: none;
}

@media (max-width: 767px) {
  .arrival_section .arrival_bg_box img {
    -o-object-position: top right;
    object-position: top right;
  }

  .arrival_section .box {
    padding: 75px 25px;
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
  .arrival_bg_box{
      display: none;
  }
}

</style>
