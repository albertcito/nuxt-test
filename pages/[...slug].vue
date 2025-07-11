<script setup lang="ts">
const route = useRoute();
</script>
<template>
    Hello {{ route.params.slug }}
    <br>
    <br>
    <NuxtLink to="/">Home</NuxtLink>
</template>
