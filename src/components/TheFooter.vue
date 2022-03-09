<template>
  <footer class="footer_section">
    <div class="container">
      <div class="row">
        <div class="col-md-4 footer-col">
          <div class="footer_contact">
            <h4>Reach at..</h4>
            <div class="contact_link_box">
              <a href="">
                <i class="fa fa-map-marker" aria-hidden="true"></i>
                <span> Location </span>
              </a>
              <a href="">
                <i class="fa fa-phone" aria-hidden="true"></i>
                <span> Call +01 1234567890 </span>
              </a>
              <a href="">
                <i class="fa fa-envelope" aria-hidden="true"></i>
                <span> demo@gmail.com </span>
              </a>
            </div>
          </div>
        </div>
        <div class="col-md-4 footer-col">
          <div class="footer_detail">
            <router-link to="/" class="footer-logo"> Famms </router-link>
            <p>
              Necessary, making this the first true generator on the Internet.
              It uses a dictionary of over 200 Latin words, combined with
            </p>
            <div class="footer_social">
              <a href="">
                <i class="fa-brands fa-facebook-f" aria-hidden="true"></i>
              </a>
              <a href="">
                <i class="fa-brands fa-twitter" aria-hidden="true"></i>
              </a>
              <a href="">
                <i class="fa-brands fa-linkedin-in" aria-hidden="true"></i>
              </a>
              <a href="">
                <i class="fa-brands fa-instagram" aria-hidden="true"></i>
              </a>
              <a href="">
                <i class="fa-brands fa-pinterest" aria-hidden="true"></i>
              </a>
            </div>
          </div>
        </div>
        <div class="col-md-4 footer-col">
          <div class="map_container">
            <div class="map">
              <div id="googleMap"></div>
            </div>
          </div>
        </div>
      </div>
      <div class="footer-info">
        <div class="col-lg-7 mx-auto px-0">
          <p>&copy; <span id="displayYear"></span> All Rights Reserved</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<style>
.footer_section {
  background-color: #002c3e;
  color: #ffffff;
  padding-top: 70px;
}

.footer_section {
  color: #ffffff;
  text-align: left;
}

.footer_section h4 {
  font-size: 28px;
}

.footer_section h4,
.footer_section .footer-logo {
  font-weight: 600;
  margin-bottom: 20px;
  font-family: "Playfair Display", serif;
  text-align: left;
}

.footer_section .footer-col {
  margin-bottom: 30px;
}

.footer_section .footer_contact .contact_link_box {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
}

.footer_section .footer_contact .contact_link_box a {
  margin: 10px 0;
  color: #ffffff;
}

.footer_section .footer_contact .contact_link_box a i {
  margin-right: 5px;
}

.footer_section .footer_contact .contact_link_box a:hover {
  color: #f7444e;
}

.footer_section .footer-logo {
  display: block;
  font-weight: bold;
  font-size: 32px;
  color: #ffffff;
}

.footer_section .footer_social {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: left;
  -ms-flex-pack: center;
  justify-content: left;
  margin-top: 25px;
  margin-bottom: 10px;
}

.footer_section .footer_social a {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  color: #002c3e;
  width: 30px;
  height: 30px;
  border-radius: 100%;
  background-color: #ffffff;
  border-radius: 100%;
  margin: 0 2.5px;
  font-size: 18px;
}

.footer_section .footer_social a:hover {
  color: #f7444e;
}

.footer_section .map_container {
  width: 100%;
  height: 175px;
  overflow: hidden;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
}

.footer_section .map_container .map {
  height: 100%;
  -webkit-box-flex: 1;
  -ms-flex: 1;
  flex: 1;
}

.footer_section .map_container .map #googleMap {
  height: 100%;
}

.footer_section .footer-info {
  text-align: center;
  margin-top: 25px;
}

.footer_section .footer-info p {
  color: #ffffff;
  margin: 0;
  padding: 20px 0;
  border-top: 1px solid rgba(255, 255, 255, 0.2);
}

.footer_section .footer-info p a {
  color: inherit;
}
</style>
