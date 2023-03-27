<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HomeHeader from './components/HomeHeader.vue'
import AsideCart from './components/AsideCart.vue'
import NavInput from './components/NavInput.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <div class="container mx-auto px-6 py-3">
        <HomeHeader />
        <nav class="sm:flex sm:justify-center sm:items-center mt-4">
          <div class="flex flex-col sm:flex-row">
            <RouterLink class="mt-3 text-gray-600 hover:underline sm:mx-3 sm:mt-0" to="/">Home</RouterLink>
            <RouterLink class="mt-3 text-gray-600 hover:underline sm:mx-3 sm:mt-0" to="/">Shop</RouterLink>
            <RouterLink class="mt-3 text-gray-600 hover:underline sm:mx-3 sm:mt-0" to="/">Categories</RouterLink>
            <RouterLink class="mt-3 text-gray-600 hover:underline sm:mx-3 sm:mt-0" to="/">Contact</RouterLink>
            <RouterLink class="mt-3 text-gray-600 hover:underline sm:mx-3 sm:mt-0" to="/about">About</RouterLink>
          </div>
        </nav>
        <NavInput />
      </div>
      <AsideCart />
    </div>
  </header>

  <footer class="bg-gray-200">
    <Footer />
  </footer>
  <RouterView />
</template>

