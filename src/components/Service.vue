<script setup>
    import CTARectangle from './CTARectangle.vue';
</script>

<template>
    <div id="service">
        <div class="content">
            <h2>Let's try our service now!</h2>
            <p>Everything you need to accept card payments and grow your business anywhere on the planet.</p>
        </div>
        <CTARectangle/>
    </div>
</template>
<style scoped>
    #service {
        max-width: 1170px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        border-radius: 20px;
        padding: 70px 100px;
        border-radius: 20px;
        background: linear-gradient(154deg, #FFF 16.15%, #6D6D6D 57.81%, #11101D 93.23%);
        backdrop-filter: blur(5px);
    }
    .content p{
        max-width: 445px;
    }
</style>