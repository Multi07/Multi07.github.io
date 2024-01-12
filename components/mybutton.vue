<script setup>
    const props = defineProps(["link"]);
</script>

<template>
    <a :href="props.link"><slot>
        default botton
    </slot></a>
</template>

<style scoped>
    a {
        background-color: red;
        color: white;
        display: inline-block;
        padding: 0.3rem;
    }
</style>

