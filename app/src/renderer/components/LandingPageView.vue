<template>
<section>
  <div>
    <!-- <img src="./LandingPageView/assets/logo.png" alt="electron-vue"> -->
    <h1>Welcome to Herbivore</h1>
    <!-- <current-page></current-page> -->
    <!-- <versions></versions> -->
    <!-- <links></links> -->
    <info/>
  </div>
  </section>
</template>

<script>
  import Links from './LandingPageView/Links'
  import Versions from './LandingPageView/Versions'
  import Info from './LandingPageView/Info'
  export default {
    components: {
      Links,
      Versions,
      Info
    },
    name: 'landing-page'
  }
</script>

<style scoped>
  img {
    margin-top: -25px;
    width: 450px;
  }
</style>
