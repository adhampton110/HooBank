<script setup>
    defineProps({
        stat: String,
        number: String,
    })
</script>
<template>
    <div class="stat">
        <h3>{{ number }}</h3>
        <p class="cyan">{{ stat }}</p>
    </div>
</template>
<style scoped>
    h3 {
        color: var(--white);
    }
    .stat {
        display: flex;
        align-items: center;
        gap: 25px;
    }
</style>