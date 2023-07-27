<script setup>
    import {airbnb,binance,coinbase,dropbox} from '../assets/';
</script>

<template>
    <section id="affiliates">
        <img :src="airbnb" alt="airbnb" class="affiliate">
        <img :src="binance" alt="binance" class="affiliate">
        <img :src="coinbase" alt="coinbase" class="affiliate">
        <img :src="dropbox" alt="dropbox" class="affiliate">
    </section>
</template>

<style scoped>
    #affiliates {
        display: flex;
        align-items: center;
        justify-content: space-around;
    }
    .affiliate {
        width: 192px;
    }
</style>