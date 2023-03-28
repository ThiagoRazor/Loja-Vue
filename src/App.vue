<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HomeHeader from './components/HomeHeader.vue'
import Footer from './components/Footer.vue'
import AsideCart from './components/AsideCart.vue'
</script>

<template>
  <header>
        <div class="wrapper">
          <HomeHeader :is-cart-show="isCartShow" @toggle-cart="toggleCart" />
            <AsideCart :class="isCartShow ? 'fixed' : 'hidden'"/>
            <div class="container m-auto px-6 py-3">
              <nav class="sm:flex sm:justify-center sm:items-center mt-4">
                <div class="flex flex-col sm:flex-row">
                  <RouterLink class="mt-3 text-gray-600 hover:underline sm:mx-3 sm:mt-0" to="/">Início</RouterLink>
                  <RouterLink class="mt-3 text-gray-600 hover:underline sm:mx-3 sm:mt-0" to="/shop">Produtos</RouterLink>
                </div>
                <RouterLink
                  class="mt-3 text-white sm:mx-3 sm:mt-0 w-24 h-12 bg-indigo-500 flex justify-center items-center rounded-xl hover:bg-indigo-600"
                  to="/signup">
                  Sign Up
                </RouterLink>
              </nav>
            </div>
          </div>
        </header>
        <RouterView />
        <footer class="bg-gray-200">
          <Footer />
        </footer>
</template>

<script>
export default{
  data(){
    return{
    isCartShow: false  
  }
  },
  methods:{
    toggleCart(){
      this.isCartShow = !this.isCartShow;
    }
  }
}
</script>


