<script setup>
import Layout from '@/Layouts/Layout.vue';
defineOptions({
    layout: Layout
});
defineProps({
    user: String
})
</script>

<template>
    <Head :title="$page.component" />
    <h1 class="text-2xl font-bold font-mono">About page</h1>
    <h3>Now we're talking about {{ user }}</h3>
</template>