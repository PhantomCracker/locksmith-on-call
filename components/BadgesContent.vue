<script setup></script>

<template>
  <div class="badges">
    <div class="container">
      <div class="row">
        <div class="col-4">
          <div class="badge">
            <NuxtImg src="/images/badges/247-service-badge.webp" alt="badge1"/>
          </div>
        </div>
        <div class="col-4">
          <div class="badge me-lg-5">
            <NuxtImg src="/images/badges/toprated.webp" alt="badge2"/>
          </div>
        </div>
        <div class="col-4">
          <div class="badge me-lg-5">
            <NuxtImg src="/images/badges/warranty.webp" alt="badge3"/>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.badges {
  background-color: rgb(44, 44, 44);
  border-bottom: solid 10px black;
  img {
    width: 100px;
  }
}
</style>