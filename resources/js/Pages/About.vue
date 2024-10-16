<script setup>
import { Head } from '@inertiajs/vue3';
defineProps({
    user: String
})
</script>

<template>

    <Head title="About" />
    <h1 class="text-2xl font-bold font-mono">About page</h1>
    <h3>Now we're talking about {{ user }}</h3>
</template>