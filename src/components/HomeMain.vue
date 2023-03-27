<template>
    <div class="container mx-auto px-6">
        <ImgContainer/>
        <div class="md:flex mt-8 md:-mx-4">
            <HardwareContainer1/>
        </div>
        <div class="mt-16">
            <h3 class="text-gray-600 text-2xl font-medium">Sugestões</h3>
            <div class="grid gap-6 grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 mt-6">
                <SugestedProduct/>
            </div>
        </div>
        <div class="mt-16">
            <h3 class="text-gray-600 text-2xl font-medium">Top Products</h3>
            <div class="grid gap-6 grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 mt-6">
                <SugestedProduct/>
            </div>
        </div>
    </div>
</template>

<script>
import ImgContainer from './ImgContainer.vue';
import HardwareContainer1 from './HardwareContainer1.vue';
import SugestedProduct from './SugestedProduct.vue';

export default{
    components:{
        ImgContainer,
        HardwareContainer1,
        SugestedProduct,
    }
}
</script>