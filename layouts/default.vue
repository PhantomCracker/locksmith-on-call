
import { NuxtPage } from '#build/components';
<template>
  <!--    Start Navbar -->
  <div class="container-fluid p-0">
    <div class="row">
      <div class="row navigation">
        <div class="d-flex justify-content-center">
          <ul class="navbar-nav h4 pt-3 pb-3">
          <li class="nav-item">
              <NuxtLink to="/" class="nav-link">Home</NuxtLink>
          </li>
          <li class="nav-item">
              <NuxtLink to="/about-us" class="nav-link">About us</NuxtLink>
          </li>
          <li class="nav-item">
              <NuxtLink to="/locksmith-near-me" class="nav-link fw-bold">Locksmith near me</NuxtLink>
          </li>
          </ul>
        </div>
      </div>
    </div>
    <div class="row navigation pt-2 pb-2">
      <div class="col-12 col-lg-6">
        <div class="navigation">
          <NuxtLink to="/">
            <img src="@/assets/logo.webp" class="logo" alt="logo" />
          </NuxtLink>
        </div>
      </div>
      <div class="col-12 col-lg-6 align-self-center">
        <div class="row justify-content-center">
          <div class="col-12 col-lg-6 align-self-center">
            <div class="justify-content-center navbar-nav pt-3">
              <div class="hero-nav-phone">
                <a href="tel:01173256595" class="nav-link ps-3 pe-3">Call us now! <br/></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!--    End Navbar-->
  <slot />
  <!--    Start Footer -->
  <div class="footer mt-3">
    <footer class="p-2" style="background: #2d3246;">
      <div class="container">
        <div class="row">
            <div class="col-sm-12 col-md-6">
              <NuxtLink to="/" class="brand"><img src="@/assets/logo.webp" alt="logo" /></NuxtLink>
              <p>We provide the best quality locksmith services with multiple teams located near you, our services include business locksmith services, emergency locksmith services, 24-hour locksmith services, with us you’ll receive trusted locksmith services in the most urgent of manner.</p>
            </div>
            <div class="d-md-none"><hr/></div>
            <div class="col-sm-12 col-md-6 align-self-center text-end">
              <ul>
                  <li>PHONE: <a href="tel:01173256595"><span>01173256595</span></a></li>
              </ul>
            </div>
        </div>
        <hr>
        <div class="row">
          <p><span>©  </span><span>2024</span><span> </span><span> Locksmith4all </span><span> - </span><span>All Rights Reserved.</span></p>
        </div>
      </div>
    </footer>
  </div>
  <!--    End Footer -->
  <a href="tel:01173256595" class="float-phone d-md-block d-lg-none">
    <Icon name="ph:phone-call" class="fa-phone" />
  </a>
</template>

<style lang="scss" scoped>
.logo {
  width: 250px;
  @media screen and (max-width: 700px)  {
    width: 95%;
  }
}
.navigation {
  padding: 0;
  margin: 0;
  background: rgb(44, 44, 44);
  ul li {
    font-size: 16px;
    text-transform: uppercase;
    a {
      color: #fff;
      padding: 0 25px;
      font-weight: 600;
    }
  }
  .navbar-nav {
    flex-direction: row;
    .nav-link {
      color: #FFFFFF;
    }
  }
  .hero-nav-phone {
    background: #B30000;
    border-radius: 10px;
    padding: 3px 12px;
  }
}
.footer {
  a, li {
    color: #fff;
    text-decoration: none;
    span {
      color: rgba(200,200,200,0.8);
    }
  }
  p {
    color: rgba(200,200,200,0.8);
  }
  hr {
    color: #ffffff;
  }
}
ul, ol {
  list-style: none;
  padding: 0;
  margin: 0;
}

@media screen and (max-width: 700px)  {
  *{padding:0;margin:0;}
  img {
    width: 100%;
    object-fit: contain;
  }
  .nav-item img {
    width: 70%;
  }
  body {
    font-family:Verdana, Geneva, sans-serif;
    font-size:18px;
    background-color:#CCC;
  }

  .float-phone {
    position:fixed;
    width:60px;
    height:60px;
    bottom:40px;
    right:40px;
    color:#FFF;
    border-radius:50px;
  }
  .fa-phone {
    width: 70px;
    height: 70px;
    background: #25D366;
    border-radius: 50px;
    padding: 12px;
    border: 2px solid rgb(44, 44, 44);
  }
}
</style>