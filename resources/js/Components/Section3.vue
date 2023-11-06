<script setup>
import Testimonial from './Testimonial.vue';
</script>
<template>
     <div class="hero min-h-screen bg-base-100 py-10">
  <div class="hero-content flex-col lg:flex-row justify-end w-full">
    <div class="w-full">
      <div class="border-b-4 w-6  border-warning"></div>
      <h3 class="text-warning mb-4">Testimonial</h3>
      <h1 class="text-5xl font-bold">Hear From Our Costumer</h1>
      <p class="py-6">Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi exercitationem quasi.</p>
      <div class="flex lg:flex-row flex-col gap-10 px-6">
        <div class="flex-1">
            <Testimonial/>
        </div>
        <div class="flex-1">
            <Testimonial/>
        </div>
        <div class="flex-1">
            <Testimonial/>
        </div>
      </div>
    </div>
  </div>
</div>
</template>