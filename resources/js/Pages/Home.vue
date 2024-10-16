<script setup>
import { Head } from '@inertiajs/vue3';

defineProps({
    user: String
})
</script>

<template>

    <Head title="Home" />
    <h1>Hello, Universe</h1>
    <h3>Now we're talking about {{ user }}</h3>
</template>
