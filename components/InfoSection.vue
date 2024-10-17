<template>
  <div class="info-section pt-4 pb-4">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-12">
          <h2 class="text-start">Cheap locksmith near me available 24/7</h2>
          <p class="text-start pt-3">At UK Local Locksmith we are proud to be able to offer our customers exceptionally diverse range of professional locksmith services. Our mission is multifold, we can provide you with 24/7 locksmith services and also provide a range of services and supplies designed to improve the security of your home or business.</p>
          <p class="text-start pt-3">Our sales and service team bring a lifetime of security experience to the table and can show you how best to protect your family, your home, and your business in today's growing crime. Our highly skilled locally based locksmiths can provide you with both commercial and residential locksmith services.</p>
        </div>
        <div class="col-lg-6 col-12 info-section-man"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "InfoSection"
}
</script>

<style scoped lang="scss">
  .info-section {
    border-top: 5px solid black;
    background-color: #ECECEC;
    .info-section-man {
      background: url('@/assets/images/infoSectionMan.webp');
      background-size: cover;
      background-repeat: no-repeat;
    }
    h5 {
      color: #3CB371;
    }
    h2 {
      color: black;
      font-family: 'Ubuntu', sans-serif;
      font-weight: 600;
    }
    p {
      color: rgb(44, 44, 44);
      font-family: 'Ubuntu', sans-serif;
      font-weight: 300;
    }
  }
  @media only screen and (max-width: 600px) {
    .info-section {
      .text-start {
        text-align: center !important;
      }
    }
  }
</style>