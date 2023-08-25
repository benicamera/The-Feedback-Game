<template>
    <div>
        <header class="shadow-sm bg-slate-400 text-white rounded-xl m-3">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="text-2xl font-bold">The Feedback Game</NuxtLink>
                <div class="flex items-center">
                    <NuxtLink to="/login" class="btn">Login</NuxtLink>
                    <NuxtLink to="/register" class="mx-2">Register</NuxtLink>
                </div>
            </nav>
        </header>
        <div class="container mx-auto p-4">
            <slot />
        </div>
        <footer>
            <div class="shadow-sm bg-slate-400 text-white rounded-xl m-3">
                <ul class="container mx-auto p-4 flex">
                    <li class="m-3">
                        <NuxtLink to="/imprint" class="">Imprint</NuxtLink>
                    </li>
                    <li class="m-3">
                        <NuxtLink to="/privacy" class="">Privacy</NuxtLink>
                    </li>
                    <li class="m-3">
                        <NuxtLink to="/terms" class="">Terms</NuxtLink>
                    </li>
                    <li class="m-3">
                        <NuxtLink to="/contact" class="">Contact</NuxtLink>
                    </li>
                </ul>
            </div>
        </footer>
    </div>
</template>

<style scoped></style>