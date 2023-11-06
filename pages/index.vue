<template>
  <div class="w-full mt-5 px-5">
    <div class="top-banner">
      <div class="grid grid-cols-3 gap-4">
        <NuxtImg class="rounded-md" src="https://beeda-primary.s3.us-east-2.amazonaws.com/public/ECI/1690453460563.jpeg" alt="banner" />
        <NuxtImg class="rounded-md" src="https://beeda-primary.s3.us-east-2.amazonaws.com/public/ECI/1690453460563.jpeg" alt="banner" />
        <NuxtImg class="rounded-md" src="https://beeda-primary.s3.us-east-2.amazonaws.com/public/ECI/1690453460563.jpeg" alt="banner" />
      </div>
    </div>
    <div class="category-section mt-5">
      <div class="flex justify-between">
        <h1 class="text-xl">Categories</h1>
        <button>View All</button>
      </div>
      <div class="flex justify-between mt-5">
        <img v-for="(i) in 12" :key="i" class="w-[80px] h-[80px]" src="@/assets/img/hamburger.png" alt="">
      </div>
    </div>
    <div class="category-section mt-5">
      <div class="flex justify-between">
        <h1 class="text-xl">Popular Items</h1>
        <button>View All</button>
      </div>
      <div class="flex justify-between mt-5">
        <img v-for="(i) in 12" :key="i" class="w-[80px] h-[80px]" src="@/assets/img/hamburger.png" alt="">
      </div>
    </div>
  </div>
</template>
<script setup>
</script>
