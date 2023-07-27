<script setup>
    import CTARectangle from '../../components/CTARectangle.vue';
</script>
<template>
    <section id="deal">
        <div class="deal-content">
            <h2>Find a better card deal in few easy steps.</h2>
            <p>Arcu tortor, purus in mattis at sed integer faucibus. Aliquet quis aliquet eget mauris tortor.ç Aliquet ultrices ac, ametau.</p>
            <CTARectangle/>
        </div>
        <img class="deal-image" src="../../assets/card.png" alt="card">
    </section>
</template>

<style scoped>
    #deal {
        display: flex;
        justify-content: space-between;
    }
    .deal-content {
        max-width: 570px;
    }
    p {
        margin-top: 24px;
        margin-bottom: 48px;
    }
    .deal-image {
        width: 513px;
        height: 449px;
    }
</style>