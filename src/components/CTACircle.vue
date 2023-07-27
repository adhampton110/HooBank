<script setup>
</script>

<template>
    <div class="circle float-right">
        <div class="flex items-end">
        <p>Get&nbsp;</p>
        <i class="arrow-up"></i>
        </div>
        <p>Started</p>
    </div>
</template>

<style scoped>
    p {
        background: var(--cyan);
        background-clip: text;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        font-weight: 500;
    }
    .circle {
        width: 140px;
        height: 140px;
        display:flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-color: transparent;
        border: 3px solid #33BBCF;
        border-radius: 100%;
        cursor: pointer;
    }
    .arrow-up {
        background-image: url('../assets/arrow-up.svg');
        width: 24px;
        height: 24px;
        background-repeat: none;
    }
</style>