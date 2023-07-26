<script setup>
    defineProps({
        percent: String,
        duration: String,
    })
</script>
<template>
    <button class="gray-gradient">
        <i class="discount-image"></i>
        <span>{{ percent }}%&nbsp;</span> DISCOUNT FOR&nbsp;<span>{{ duration }}</span>&nbsp;ACCOUNT
    </button>
</template>

<style scoped>
button {
    display: flex;
    padding: 6px 10px;
    justify-content: space-between;
}
    .discount-image {
        background-image: url('../assets/Discount.svg');
        width: 32px;
        height: 32px;
    }
    span {
        color: var(--white);
    }
    button {
        width: 408px;
        border-radius: 10px;
    }
</style>