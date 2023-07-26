<script setup>
    defineProps({
        percent: String,
        duration: String,
    })
</script>
<template>
    <button class="gray-gradient"><span>{{ percent }}</span>% DISCOUNT FOR <span>{{ duration }}</span>ACCOUNT</button>
</template>

<style scoped>
    span {
        color: var(--white);
    }
    button {
        border-radius: 10px;
    }
</style>