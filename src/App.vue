<script setup>
  import Navbar from './components/Navbar.vue';
</script>
<template>
  <div class="mobile-page ">
    <Navbar/>
    <router-view/>
  </div>
</template>
<style >
  @media (min-width: 1024px) {
    .mobile-page{
      width: 750px;
      margin: 0 auto;
    }
  }
</style>

