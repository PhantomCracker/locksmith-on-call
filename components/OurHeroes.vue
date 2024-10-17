<script setup></script>

<template>
  <div class="heroes pb-5">
    <div class="container">
      <div class="row">
        <div class="col-12 pt-5 pb-4">
          <h2 class="text-center" style="color: #B30000">Why to choose Local Locksmith 4 All</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-12">
          <div class="heroes-services d-block d-md-flex">
            <div class="card p-3 w-100 ms-lg-3 mt-3 mt-lg-0">
              <div class="card-body p-3">
                <h2> 01 </h2>
                <h3 class="card-title pt-2"> Best customer experience</h3>
                <p class="card-text pt-5">When you call, we will give you as much help and information as possible over the phone.</p>
              </div>
            </div>
            <div class="card p-3 w-100 ms-lg-3 mt-3 mt-lg-0">
              <div class="card-body p-3">
                <h2> 02 </h2>
                <h3 class="card-title pt-2"> Crafted by the best </h3>
                <p class="card-text pt-5">We only use high-quality, branded locks and parts we've worked with for years and know are reliable.</p>
              </div>
            </div>
            <div class="card p-3 w-100 ms-lg-3 mt-3 mt-lg-0">
              <div class="card-body p-3">
                <h2> 03 </h2>
                <h3 class="card-title pt-2"> Insurance Approved </h3>
                <p class="card-text pt-5">Our 12-month Guarantee covers parts and workmanship on all our work. So, if anything goes wrong, we'll be back to sort it the same day you report it.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
  .heroes {
    background: rgb(44, 44, 44);
    h1, h2 {
      color: #FFFFFF;
      font-weight: 700;
    }
    .heroes-services {
      .card {
        background: rgb(44, 44, 44);
        border: 3px dotted #B30000;
        &:hover {
          background: -webkit-linear-gradient(top, #B30000 0%, #ff0078 100%),-webkit-linear-gradient(right, #B30000 0%, #ff0078 100%);
        }
        .card-text {
          color: #FFFFFF;
        }
        .card-title {
          color: #FFFFFF;
          font-weight: 600;
          font-family: Montserrat, 'sans-serif';
        }
      }
    }
  }
</style>