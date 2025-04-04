<script setup></script>

<template>
  <div class="our-services pt-5 pb-5">
    <div class="container">
      <div class="row">
        <div class="col-12 col-lg-3">
          <div class="card w-100">
            <div class="card-body">
              <h5 class="card-title">EMERGENCY LOCKSMITH</h5>
              <div class="card-text">
                <ul>
                  <li>24/7 Emergency Service</li>
                  <li>Lock repairs</li>
                  <li>Safe Opening</li>
                  <li>Card access & keypad locking</li>
                  <li>Security lock systems</li>
                </ul>
              </div>
              <button class="btn btn-primary w-50 mt-3 mb-4">
                <a class="text-white text-decoration-none" href="tel:03307890914"><Icon name="ph:phone-call" class="fa-phone" />Call now</a>
              </button>
            </div>
          </div>
        </div>
        <div class="col-12 col-lg-3">
          <div class="card w-100">
            <div class="card-body">
              <h5 class="card-title">LOCK CHANGE</h5>
              <div class="card-text">
                <ul>
                  <li>Lock Replacement</li>
                  <li>Lock-Box Installation</li>
                  <li>Lock-Box Repair</li>
                  <li>Lock Repairs</li>
                  <li>Security lock systems</li>
                </ul>
              </div>
              <button class="btn btn-primary w-50 mt-3 mb-4">
                <a class="text-white text-decoration-none" href="tel:03307890914"><Icon name="ph:phone-call" class="fa-phone" />Call now</a>
              </button>
            </div>
          </div>
        </div>
        <div class="col-12 col-lg-3">
          <div class="card w-100">
            <div class="card-body">
              <h5 class="card-title">BURGLARY REPAIR</h5>
              <div class="card-text">
                <ul>
                  <li>Post Break-In Lock Service</li>
                  <li>Security Upgrade</li>
                  <li>Window and Patio Door Locks</li>
                  <li>Insurance Approved Locks</li>
                  <li>24/7 Emergency Service</li>
                </ul>
              </div>
              <button class="btn btn-primary w-50 mt-3 mb-4">
                <a class="text-white text-decoration-none" href="tel:03307890914"><Icon name="ph:phone-call" class="fa-phone" />Call now</a>
              </button>
            </div>
          </div>
        </div>
        <div class="col-12 col-lg-3">
          <div class="card w-100">
            <div class="card-body">
              <h5 class="card-title">COMMERCIAL PRICES</h5>
              <div class="card-text">
                <ul>
                  <li>Lock Replacement</li>
                  <li>24/7 Emergency Service</li>
                  <li>Window and Patio Door Locks</li>
                  <li>UPVC Door Lock Repair / Replace</li>
                  <li>24/7 Emergency Service</li>
                </ul>
              </div>
              <button class="btn btn-primary w-50 mt-3 mb-4">
                <a class="text-white text-decoration-none" href="tel:03307890914"><Icon name="ph:phone-call" class="fa-phone" />Call now</a>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
  .our-services {
    .col-12, .col-lg-3 {
      padding-left: 0;
      padding-right: 0;
    }
    .card {
      border-radius: 0;
      min-height: 290px;
      border: none;
      border-bottom: 1px solid #ededed;
      .card-body {
        border-left: 10px solid #3CB371;
        padding: 0;
        display: flex;
        flex-direction: column;
        button {
          margin: 0 auto;
        }
      }
      .card-title {
        border-bottom: 1px solid #ededed;
        background: black;
        color: #FFFFFF;
        padding-top: 20px;
        padding-bottom: 20px;
        text-align: center;
        min-height: 90px;
      }
      .card-text {
        ul {
          text-decoration: none;
          list-style-type: none;
          text-align: left;
          padding-left: 0;
          font-family: sans-serif;
          li {
            border-bottom: 1px solid #ededed;
            font-size: 13px;
            padding-left: 10px;
            padding-top: 10px;
            padding-bottom: 10px;
            color: #787878;
          }
        }
      }
    }
    .btn-primary {
      background-color: #3CB371 !important;
      border: none;
      border-radius: 0;
      &:focus, :active, :target, :visited {
        border: none;
        box-shadow: none;
      }
      a {
        text-align: center;
      }
    }
  }
</style>