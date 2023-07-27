<script setup>
    import {airbnb,binance,coinbase,dropbox} from '../assets/';
</script>

<template>
    <section id="affiliates">
        <img :src="airbnb" alt="" class="affiliate">
        <img :src="binance" alt="" class="affiliate">
        <img :src="coinbase" alt="" class="affiliate">
        <img :src="dropbox" alt="" class="affiliate">
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