<template>
    <div>
        <p>this is the product id page {{ id }}</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params

    definePageMeta({
        layout: 'products'
    })

</script>

<style scoped>

</style>