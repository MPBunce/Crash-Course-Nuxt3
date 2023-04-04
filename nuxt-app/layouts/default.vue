<template>
    <div>

        <header class="shadow-small bg-white">
            <nav>

                <NuxtLink to="/">da main</NuxtLink>

                <ul>
                    <li><NuxtLink to="/">home</NuxtLink></li>
                    <li><NuxtLink to="/about">about</NuxtLink></li>
                    <li><NuxtLink to="products">products</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <div>

            <slot />

        </div>

        <h1 class="text-3xl font-bold underline bg-red-200">
            Hello world!
        </h1>

    </div>
</template>