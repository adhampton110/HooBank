<script setup>
</script>

<template>
    <nav class="flex justify-between items-center">
        <img src="../assets/logo.svg" alt="logo">
        <div class="links">
            <a class="active" href="#">Home</a>
            <a href="#">About Us</a>
            <a href="#">Features</a>
            <a href="#">Solution</a>
        </div>
    </nav>
</template>

<style scoped>
    img {
        height: 40px;
    }
    .links {
        display: flex;
        gap: 56px;
    }
    .active {
        color: var(--white);
    }
</style>