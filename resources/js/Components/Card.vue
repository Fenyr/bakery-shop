<script setup>
const props = defineProps({
    title: {
        type: String,
        default: 'Cakes',
    },
    price: {
        type: String,
        default: 'Rp.10.000',
    },
    image: {
        type: String,
        default: 'https://htmlcolorcodes.com/assets/images/colors/gray-color-solid-background-1920x1080.png',
    },
    rating: {
        type: String,
        default: '5',
    },
    url: {
        type: String,
        default: '5',
    },
});
</script>
<template>
  <a href="">
    <div class="card w-full bg-base-100 shadow-xl rounded-lg">
  <figure><img src='{{ image }}' alt="Cakes" class="h-40 bg-gray-400 w-full object-cover" /></figure>
  <div class="card-body">
    <h2 class="card-title">{{ price }}</h2>
    <p>{{ title }}</p>
    <div class="rating">
  <input name="rating-2" class="mask mask-star-2 bg-orange-400" />
  <input name="rating-2" class="mask mask-star-2 bg-orange-400" />
  <input name="rating-2" class="mask mask-star-2 bg-orange-400" />
  <input name="rating-2" class="mask mask-star-2 bg-orange-400" />
  <input name="rating-2" class="mask mask-star-2 bg-orange-400" />
</div>
  </div>
</div>
  </a>
</template>