<script setup>
import Card from '@/Components/Card.vue';
</script>

<template>
    <div class="hero w-full bg-base-200 min-h-screen">
  <div class="hero-content flex-col md:flex-row">
    <div>
      <div class="border-b-4 w-6  border-warning"></div>
      <h3 class="text-warning mb-4">Explore</h3>
      <h1 class="text-5xl font-bold">Hot Selling</h1>
      <p class="py-6">Provident cupiditate voluptatem et in. <br> Quaerat fugiat ut assumenda excepturi exercitationem quasi. In deleniti eaque aut repudiandae et a id nisi.</p>
    </div>

    <div class="carousel max-w-[26rem] md:max-w-2xl carousel-center px-2 py-8 md:space-x-8 space-x-4 bg-base-200 rounded-box">
  <div class="carousel-item">
    <Card/>
  </div> 
  <div class="carousel-item">
    <Card/>
  </div> 
  <div class="carousel-item">
    <Card/>
  </div> 
  <div class="carousel-item">
    <Card/>
  </div> 
  <div class="carousel-item">
    <Card/>
  </div> 
  <div class="carousel-item">
    <Card/>
  </div> 
  
</div>
  </div>
</div>
</template>