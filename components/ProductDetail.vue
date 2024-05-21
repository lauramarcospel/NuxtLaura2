<template>
    <div class="grid grid-cols-2">
        <div>
            <img :src="Product.image" alt="">
         </div>
         <div>
        <h2>{{ product.title }}</h2>
        <p>{{ product.price }}</p>
        <h3>{{ product.description }}</h3>
    </div>
    </div>
   
</template>

<script setup>
const { product } = defineProps(["product"])
</script>

<style scoped>

</style>