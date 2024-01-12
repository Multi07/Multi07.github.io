<script setup>
    const props = defineProps(["link"]);
</script>

<template>
    <NuxtLink :to="props.link"><slot>
        default botton
    </slot></NuxtLink>
</template>

<style scoped>
    a {
        background-color: red;
        color: white;
        display: inline-block;
        padding: 0.3rem;
    }
</style>

