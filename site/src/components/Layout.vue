<template>
    <div class="flex flex-col min-h-screen">
        <TopBar />
        <main class="flex-grow p-4">
            <slot></slot>
        </main>
        <Footer />
    </div>
</template>

<script setup>
import TopBar from "./TopBar.vue";
import Footer from "./Footer.vue";
</script>