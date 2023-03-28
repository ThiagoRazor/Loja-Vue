
<template>
    <div
        class="right-0 top-0 max-w-xs w-full h-full px-6 py-4 transition duration-300 transform overflow-y-auto bg-white border-l-2 border-gray-300 z-30">
        <div class="flex items-center justify-between">
            <h3 class="text-2xl font-medium text-gray-700">Carrinho</h3>
        </div>
        <hr class="my-3">
        <CartItens />
        <a
            class="flex items-center justify-center mt-4 px-3 py-2 bg-blue-600 text-white text-sm uppercase font-medium rounded hover:bg-blue-500 focus:outline-none focus:bg-blue-500">
            <span>Checkout</span>
            <svg class="h-5 w-5 mx-2" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                viewBox="0 0 24 24" stroke="currentColor">
                <path d="M17 8l4 4m0 0l-4 4m4-4H3"></path>
            </svg>
        </a>
    </div>
</template>

<script>
import CartItens from './CartItens.vue'

export default {
    components:{
        CartItens
    }
}
</script>
