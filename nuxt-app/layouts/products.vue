<template>
    <div class="bg-blue">
        <header>
            <nav>

                <NuxtLink to="/">da main</NuxtLink>

            </nav>
        </header>

        <slot/>

    <ul>
        <li><NuxtLink to="/">home</NuxtLink></li>
         <li><NuxtLink to="/about">about</NuxtLink></li>
         <li><NuxtLink to="products">products</NuxtLink></li>
    </ul>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>