<template>
  <div class="header_section">
    <nav class="navbar navbar-expand-lg custom_nav-container">
      <div class="container">
        <router-link class="navbar-brand" to="/"
          ><img width="250" src="../assets/images/logo.png" alt=""
        /></router-link>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class=""></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link class="nav-link active" aria-current="page" to="/"
                >Home</router-link
              >
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Pages
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li>
                  <router-link class="dropdown-item" to="/about"
                    >About</router-link
                  >
                </li>
                <li><router-link class="dropdown-item" to="/testimonial">Testimonial</router-link></li>
              </ul>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/product">Products</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/blog">Blog</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/contact">Contact</router-link>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"
                ><i class="fa-solid fa-cart-shopping icon-fa"></i
              ></a>
            </li>
            <li class="nav-item">
              <a class="nav-link nav_search-btn" href="#"
                ><i class="fa-solid fa-magnifying-glass icon-fa"></i
              ></a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<style scoped>
.header_section {
  padding: 15px 0;
}

.header_section .container-fluid {
  padding-right: 25px;
  padding-left: 25px;
}
.custom_nav-container {
  padding: 0;
}

.custom_nav-container .navbar-nav {
  margin-left: auto;
}
.custom_nav-container .navbar-nav .nav-item .nav-link {
  padding: 5px 20px;
  color: #131313;
  text-align: center;
  text-transform: uppercase;
  border-radius: 5px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  font-weight: 700;
}
.custom_nav-container .navbar-nav .nav-item .nav-link .icon-fa {
  width: 17px;
  height: auto;
  fill: #000000;
  margin-bottom: 2px;
}
.custom_nav-container .navbar-nav .nav-item:hover .nav-link,
.custom_nav-container .navbar-nav .nav-item.active .nav-link {
  color: #f7444e;
}

.custom_nav-container .navbar-nav .nav-item:hover .nav-link .icon-fa,
.custom_nav-container .navbar-nav .nav-item.active .nav-link .icon-fa {
  fill: #f7444e;
}
.custom_nav-container .navbar-toggler {
  outline: none;
}
.navbar-toggler:focus {
  box-shadow: none !important;
}
.custom_nav-container .navbar-toggler {
  padding: 0;
  width: 37px;
  height: 42px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

.custom_nav-container .navbar-toggler span {
  display: block;
  width: 35px;
  height: 4px;
  background-color: #000000;
  margin: 7px 0;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  position: relative;
  border-radius: 5px;
  transition: all 0.3s;
}

.custom_nav-container .navbar-toggler span::before,
.custom_nav-container .navbar-toggler span::after {
  content: "";
  position: absolute;
  left: 0;
  height: 100%;
  width: 100%;
  background-color: #000000;
  top: -10px;
  border-radius: 5px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

.custom_nav-container .navbar-toggler span::after {
  top: 10px;
}

.custom_nav-container .navbar-toggler[aria-expanded="true"] {
  -webkit-transform: rotate(360deg);
  transform: rotate(360deg);
}

.custom_nav-container .navbar-toggler[aria-expanded="true"] span {
  -webkit-transform: rotate(45deg);
  transform: rotate(45deg);
}

.custom_nav-container .navbar-toggler[aria-expanded="true"] span::before,
.custom_nav-container .navbar-toggler[aria-expanded="true"] span::after {
  -webkit-transform: rotate(90deg);
  transform: rotate(90deg);
  top: 0;
}

/* .nav-link:hover, .nav-link:focus {
    color: #f7444e !important;
} */

.router-link-exact-active,
.router-link-active {
  color: #f7444e !important;
}

/* li.nav-item ul {
    background: #fff;
    border: solid #000 2px;
    border-radius: 0;
    padding: 10px 20px;
    margin-left: 10px;
    margin-top: 10px;
    box-shadow: 4px 4px 0px 0 #000;
    width: 190px;
} */

@media (max-width: 992px) {
  .custom_nav-container .navbar-nav {
    padding-top: 15px;
    align-items: center;
  }

  .custom_nav-container .navbar-nav .nav-item .nav-link {
    padding: 5px 25px;
    margin: 5px 0;
  }
}
</style>
