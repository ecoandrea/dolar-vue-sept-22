<script setup>
import CardMoney from "./components/CardMoney.vue";
import Navbar from "./components/Navbar.vue";
</script>

<template>
<Navbar />

  <div class="container mx-auto px-4">
    <h1 class="font-light text-center text-blue-600">API DOLAR</h1>
    <main class="grid grid-cols-1 sm:grid-cols-4 gap-2 pt-5">
      <CardMoney />
      <CardMoney />
      <CardMoney />
      <CardMoney />
    </main>
  </div>
</template>
