<script>
import Product from '../components/Product.vue'

export default {
    components:{
        Product,
    }
}
</script>
<template>
    <!-- component -->
<section class="bg-white">
        <div class="container px-6 py-8 mx-auto">
            <div class="lg:flex lg:-mx-2">
                <div class="space-y-3 lg:w-1/5 lg:px-2 lg:space-y-4">
                    <a href="#" class="block font-medium text-gray-500 hover:underline">Playstation 4</a>
                </div>

                <div class="mt-6 lg:mt-0 lg:px-2 lg:w-4/5 ">
                    <div class="flex items-center justify-between text-sm tracking-widest uppercase ">
                        <p class="text-gray-500">6 Items</p>
                        <div class="flex items-center">
                            <p class="text-gray-500 ">Sort</p>
                            <select class="font-medium text-gray-700 bg-transparent focus:outline-none">
                                <option value="#">Recommended</option>
                                <option value="#">Size</option>
                                <option value="#">Price</option>
                            </select>
                        </div>
                    </div>
                    <Product/>
                </div>
            </div>
        </div>
    </section>
</template>