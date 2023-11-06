<script setup>
import Gmap from './Gmap.vue';
</script>

<template>
     <div id="map" class="hero bg-base-100 pb-10">
  <div class="hero-content flex-col lg:flex-row justify-start w-full">
    <div class="w-full">
      <div class="border-b-4 w-6  border-warning"></div>
      <h3 class="text-warning mb-4">Direction</h3>
      <h1 class="text-5xl font-bold">Pickup Location</h1>
      <p class="py-6">Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi exercitationem quasi.</p>
      <Gmap/>
    </div>
  </div>
</div>
  </template>