<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <nav class="bg-gradient-to-r from-blue-500 via-purple-500 to-blue-400 shadow-lg py-4 px-8 flex justify-between items-center">
      <div class="text-white text-2xl font-bold tracking-wide">MyBrand</div>
      <div class="space-x-6">
        <RouterLink class="text-white hover:text-yellow-300 transition duration-300 text-lg font-medium" to="/">Home</RouterLink>
        <RouterLink class="text-white hover:text-yellow-300 transition duration-300 text-lg font-medium" to="/about">About</RouterLink>
        <RouterLink class="text-white hover:text-yellow-300 transition duration-300 text-lg font-medium" to="/contact">Contact</RouterLink>
        <RouterLink class="text-white hover:text-yellow-300 transition duration-300 text-lg font-medium" to="/user">User List</RouterLink>
      </div>
    </nav>
  </header>

  <RouterView />
</template>
