<script setup></script>

<template>
  <div class="hero">
    <div class="container">
      <div class="row flex-column-reverse flex-lg-row">
        <div class="col-12 col-lg-6 hero-man"></div>
        <div class="col-12 col-lg-6 pb-3">
          <h1>Local Locksmith near me</h1>
          <ul class="bg-black">
            <li class="pt-2">Service on spot within 25 minutes</li>
            <li>Local service from £39</li>
            <li>Locks from £25</li>
            <li>24/7 Local Emergency</li>
            <li>Fully equipped locksmiths</li>
            <li>No Call Out Charge</li>
            <li>1 Year Warranty</li>
            <div class="d-md-none d-sm-block">
              <ul class="p-0">
                <li>100% Satisfaction Guarantee</li>
                <li>Local Locksmiths</li>
                <li>Mobile service, we come to you</li>
                <li>Licensed & insured professionals.</li>
                <li>24/7 availability, for your peace of mind</li>
                <li>Fast & efficient</li>
                <li>Trustworthy</li>
                <li>Reliable & Secure</li>
                <li>Quick & Convenient</li>
                <li>Local expertise</li>
                <li>Satisfaction guarantee</li>
                <li class="pb-2">Expert security consultationse</li>
              </ul>
            </div>
          </ul>
          <button class="btn btn-primary w-100 mt-1">
            <a class="text-white text-decoration-none" href="tel:03307890914">At your location within 25 minutes</a>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.hero {
  background-image: url("@/assets/images/hero-background.webp");
  background-size: cover;
  background-repeat: no-repeat;
  border-bottom: 10px solid #000000;

  @media (max-width: 700px) {
    max-height: 100%;
    background-image: none;
    background-color: #000000;
  }

  .hero-man {
    background-image: url("@/assets/images/header-man.webp");
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
    min-height: 300px;
    @media (max-width: 700px) {
      border-top: 10px solid black;
    }
  }
  li {
    font-family: 'Ubuntu', sans-serif;
    list-style: disc;
    color: #fff;
  }
}
h1 {
  font-size: 2.5rem;
  color: #fff;
}
.btn-primary {
  background-color: #3CB371 !important;
  border: none;
  &:focus, :active, :target, :visited {
    border: none;
    box-shadow: none;
  }
  a {
    text-align: center;
  }
}
</style>
