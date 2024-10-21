<script setup>
const route = useRoute();
useHead({
    script: [
      { 
        src: "//s.ksrndkehqnwntyxlhgto.com/95446.js",
        defer: true
      }
    ],
});
</script>

<template>
    <Html lang="en">
        <Head>
            <Meta name="description" :content="`24/7 emergency locksmith services in ${route.params.cities}. Locksmith on call also provide a range of services and supplies designed to improve the security of your home or business`" />
            <Title>Locksmith in {{ route.params.cities }}</Title>
        </Head>
    </Html>
    <NuxtLayout>
        <div class="city hero">
            <div class="container">
                <div class="row pt-4 d-flex flex-column-reverse flex-lg-row">
                    <div class="col-lg-6 col-sm-12 d-sm-none d-md-block hero-man pt-3"></div>
                    <div class="col-lg-6 col-sm-12 d-flex align-self-center flex-column mt-3 mt-md-0 pb-4">
                    <h1 class="text-white text-start"><span class="my-yellow">Locksmith</span> in {{ route.params.cities }}</h1>
                    <ul class="with-border bg-black">
                        <li class="text-white text-start pl-2 pt-3">Service on spot withing 25 minutes</li>
                        <li class="text-white text-start pl-2">Local service from £39</li>
                        <li class="text-white text-start pl-2 pb-3">Locks from £25</li>
                    </ul>
                    <button class="btn btn-primary w-100 my-primary-btn mt-3">
                        <a class="text-white text-decoration-none" href="tel:01173256595">At your location within 25 minutes</a>
                    </button>
                    </div>
                </div>
            </div>
            <ServicesCard />
            <OurServices />
            <InfoSection />
            <OurHeroes />
        </div>
    </NuxtLayout>
</template>

<style scoped lang="scss">
.hero {
  background-image: url("@/assets/images/hero-background.webp");
  background-size: cover;
  background-repeat: no-repeat;
  max-height: 500px;
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
  }
}
h1 {
  font-size: 2.5rem;
  &.with-border {
    border-left: 10px solid #3CB371;
    padding-left: 25px;
    @media (max-width: 700px) {
      font-size: 3.5rem;
    }
  }
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