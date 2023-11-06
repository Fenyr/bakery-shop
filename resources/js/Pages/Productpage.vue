<script setup>
import { Head, Link } from '@inertiajs/vue3';
import Navbar from '@/Components/Navbar.vue';
import Footer from '@/Components/Footer.vue';
import Card from '@/Components/Card.vue';

</script>

<template>
   <Navbar />

   <div class="min-h-screen w-full bg-base-100 flex flex-col items-center px-2 py-4">
    <h2 class="text-5xl font-bold">Our menu</h2>
    <div class="rounded-full px-8 py-2 bg-base-200 text-xs lg:text-base flex gap-8 my-4">
        <button class="bg-warning/80 px-2 py-1 rounded-full w-16">All</button>
        <button>Cakes</button>
        <button>Cookies</button>
        <button>Breads</button>
        <button>Drink</button>
    </div>
    <div class=" px-8 grid lg:grid-cols-6 grid-cols-2 gap-4 py-6">
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
   </div>
   <div class="join py-4">
  <button class="join-item btn btn-active">1</button>
  <button class="join-item btn">2</button>
  <button class="join-item btn">3</button>
  <button class="join-item btn">4</button>
</div>
   </div>

   

   <Footer/>

</template>

<style>

</style>
