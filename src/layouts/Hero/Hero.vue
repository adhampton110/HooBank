<script setup>
import Navbar from '../../components/Navbar.vue';
import Discount from '../../components/Discount.vue';
import CTACircle from '../../components/CTACircle.vue';
</script>

<template>
    <section id="hero">
        <Navbar/>
        
        <div class="flex items-center mt-[70px]">
            <div class="hero-content">
                <Discount percent="20" duration="1 MONTH"/>
                <div>
                    <CTACircle/>
                    <h1>The Next <span class="cyan">Generation</span> Payment Method.</h1>
                </div>
                <p>
                    Our team of experts uses a methodology to identify the credit cards most likely to fit your needs. 
                    We examine annual percentage rates, annual fees.
                </p>
            </div>
            <img class="hero-image" src="../../assets/robot.png" alt="robot">
        </div>  
    </section>
</template>

<style scoped>
    .hero-content p {
        max-width: 483px;
        text-align: left;
    }
    .hero-image {
        width: 669px;
    }
</style>