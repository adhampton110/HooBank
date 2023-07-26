<script setup>
import Navbar from '../../components/Navbar.vue';
import Discount from '../../components/Discount.vue';
</script>

<template>
    <section id="hero">
        <Navbar/>
        <Discount percent="20" duration="1 MONTH"/>
        <div class="flex">
            <div class="hero-content">
                <h1>Next <span>Generation</span> Payment Method.</h1>
                <p>
                    Our team of experts uses a methodology to identify the credit cards most likely to fit your needs. 
                    We examine annual percentage rates, annual fees.
                </p>
            </div>
        </div>  
    </section>
</template>

<style scoped></style>