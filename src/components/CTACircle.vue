<script setup>
</script>

<template>
    <div class="circle">
        <p>Get</p>
        <i class="arrow-up"></i>
        <p>Started</p>
    </div>
</template>

<style scoped>
    p {
        background: linear-gradient(180deg, #DEF9FA 0.89%, #BEF3F5 17.23%, #9DEDF0 42.04%, #7DE7EB 55.12%, #5CE1E6 71.54%, #33BBCF 100%);
        background-clip: text;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        font-weight: 500;
    }
    .circle {
        width: 140px;
        height: 140px;
        display:flex;
        justify-content: center;
        align-items: center;
        background-color: orange;
        border-radius: 100%;
    }
    .arrow-up {
        background-image: url('../assets/arrow-up.svg');
        width: 24px;
        height: 24px;
        background-repeat: none;
    }
</style>