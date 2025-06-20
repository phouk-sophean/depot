<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <nav
      class="bg-gradient-to-r from-blue-500 via-purple-500 to-blue-400 shadow-lg py-3 md:py-4 px-4 md:px-8 flex flex-col sm:flex-row justify-between items-center gap-4 sm:gap-0"
    >
      <div class="text-white text-xl md:text-2xl font-bold tracking-wide">
        MyBrand
      </div>
      <div class="flex flex-wrap justify-center sm:justify-end gap-4 md:gap-6">
        <RouterLink
          class="text-white hover:text-yellow-300 transition duration-300 text-base md:text-lg font-medium"
          to="/"
          >Home</RouterLink
        >
        <RouterLink
          class="text-white hover:text-yellow-300 transition duration-300 text-base md:text-lg font-medium"
          to="/about"
          >About</RouterLink
        >
        <RouterLink
          class="text-white hover:text-yellow-300 transition duration-300 text-base md:text-lg font-medium"
          to="/contact"
          >Contact</RouterLink
        >
        <RouterLink
          class="text-white hover:text-yellow-300 transition duration-300 text-base md:text-lg font-medium"
          to="/user"
          >User List</RouterLink
        >
      </div>
    </nav>
  </header>

  <RouterView />
</template>
