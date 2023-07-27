<script setup>
import Navbar from '../../components/Navbar.vue';
import Discount from '../../components/Discount.vue';
import CTACircle from '../../components/CTACircle.vue';
import VerticleLine from '../../components/VerticleLine.vue';
import Stat from '../../components/Stat.vue';
</script>

<template>
    <section id="hero">
        <Navbar/>
        <div class="flex items-center justify-between mt-[70px]">
            <div class="hero-content">
                <Discount percent="20" duration="1 MONTH"/>
                <div class="mb-[70px] mt-[20px]">
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
        <div class="company-stats">
            <Stat number="3800+" stat="USER ACTIVE"/>
            <VerticleLine/>
            <Stat number="230+" stat="TRUSTED BY COMPANY"/>
            <VerticleLine/>
            <Stat number="$230M+" stat="TRANSACTION"/>
        </div>
    </section>
</template>

<style scoped>
    .hero-content {
        max-width: 670px;
    }
    .hero-content p {
        max-width: 483px;
        text-align: left;
        
    }
    .hero-image {
        max-width: 669px;
    }
    .company-stats {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
</style>