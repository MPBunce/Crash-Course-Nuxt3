<template>
    <div class="card">
        <div class="grid grid-cols-2 gap-10">

            <div class="p-7">
                <img :src="product.image" alt="product" class="mx-auto my-7">
            </div>

            <div class="p-7">
                <h2>{{ product.title }}</h2>
                <p>{{ product.price }}</p>
                <h3>Product description</h3>
                <p>{{ product.description }}</p>
            </div>

        </div>
    </div>
</template>




<script setup>
    const {product} = defineProps(['product'])
</script>