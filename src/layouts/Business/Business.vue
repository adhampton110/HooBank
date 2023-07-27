<script setup>
    import CTARectangle from '../../components/CTARectangle.vue';
</script>
<template>
    <section id="business">
        <div>
            <h2>You do the business, we'll handle the money</h2>
            <p class="description">
                With the right credit card, you can improve your financial life by building credit, earning rewards and saving money. But with hundreds of credit cards on the market.
            </p>
            <CTARectangle/>
        </div>
        <div class="business-items">
            <div class="rewards">
                <div class="img-wrapper"><img src="../../assets/Star.svg" alt="start"></div>
                <div>
                    <h4>Rewards</h4>
                    <p class="content">
                        The best credit cards offer some tantalizing combinations of promotions and prizes
                    </p>
                </div>
            </div>
            <div class="secured wht-blk-gradient">
                <div class="img-wrapper"><img src="../../assets/Shield.svg" alt="shield"></div>
                <div>
                    <h4>100% Secured</h4>
                    <p class="content">
                        We take proactive steps make sure your information and transactions are secure.
                    </p>
                </div>
            </div>
            <div class="balance">
                <div class="img-wrapper"><img src="../../assets/Send.svg" alt="send"></div>
                <div>
                    <h4 class="mb-2">Balance Transfer</h4>
                    <p class="content">
                        A balance transfer credit card can save you a lot of money in interest charges.
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped>
    .description {
        margin-top: 24px;
        margin-bottom: 68px;
    }
    .img-wrapper {
        width: 64px;
        height: 64px;
        background-color: var(--transparent-turquoise);
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 50%;
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
        width: 470px;
        cursor: pointer;
        border-radius: 20px;
        padding: 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .content {
        margin-top: 8px;
        font-size: 16px;
        width: 346px;
        line-height: normal;
    }
</style>