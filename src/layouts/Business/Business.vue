<script setup>
    import CTARectangle from '../../components/CTARectangle.vue';
</script>
<template>
    <section id="business">
        <div>
            <h2>You do the business, we'll handle the money</h2>
            <p>
                With the right credit card, you can improve your financial life by building credit, earning rewards and saving money. But with hundreds of credit cards on the market.
            </p>
            <CTARectangle/>
        </div>
        <div class="business-items">
            <div class="rewards">
                <img src="../../assets/Star.svg" alt="start">
                <div>
                    <h4>Rewards</h4>
                    <p class="content">
                        The best credit cards offer some tantalizing combinations of promotions and prizes
                    </p>
                </div>
            </div>
            <div class="secured active">
                <img src="../../assets/Shield.svg" alt="shield">
                <div>
                    <h4>100% Secured</h4>
                    <p class="content">
                        We take proactive steps make sure your information and transactions are secure.
                    </p>
                </div>
            </div>
            <div class="balance">
                <img src="../../assets/Send.svg" alt="send">
                <div>
                    <h4>Balance Transfer</h4>
                    <p class="content">
                        A balance transfer credit card can save you a lot of money in interest charges.
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped>
    img {
        padding: 12px;
        background-color: rgba(9, 151, 124, 0.10);
        border-color: rgba(9, 151, 124, 0.10);
    }
    #business {
        display: flex;
        align-items: center;
    }
    .business-items {
        display: flex;
        flex-direction: column;
        gap: 36px;
    }
    .rewards,.secured,.balance {
        display: flex;
        align-items: center;
    }
    .active {
        border-radius: 20px;
        background: linear-gradient(154deg, rgba(255, 255, 255, 0.00) 0%, #14101D 100%);
        box-shadow: 0px 20px 100px -10px rgba(66, 71, 91, 0.10);
    }
    .content {
        font-size: 16px;
    }
</style>