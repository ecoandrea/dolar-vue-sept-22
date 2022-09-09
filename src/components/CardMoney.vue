<script setup>
import IconDolar from "./icons/IconDolar.vue";
import IconUp from "./icons/IconUp.vue";
import IconDown from "./icons/IconDown.vue";
</script>

<template>
  <article
    class="relative p-4 text-center text-gray-100 bg-gray-800 rounded-md"
  >
    <span
      class="absolute top-0 left-0 right-0 h-1 bg-white rounded-t-md bg-gradient-to-r from-pink-300 to-pink-600"
    ></span>
    <div
      class="absolute flex justify-center w-8 h-8 -translate-x-1/2 bg-gray-500 rounded-full -top-4 left-1/2"
    >
      <IconDolar class="w-3 fill-gray-100" />
    </div>
    <h2>Dolar</h2>
    <h3 class="py-4 text-4xl">$850</h3>
    <p class="flex justify-center gap-1">
      <IconUp class="w-2 fill-green-500" />
      <IconDown class="w-2 fill-red-600" />
      <span>0.05%</span>
    </p>
  </article>
</template>
