<template>
    <section id="control">
        <img class="bill-image" src="../../assets/bill.png" alt="bill">
        <div class="content">
            <h2>Easily control your billing & invoicing.</h2>
            <p>
                Elit enim sed massa etiam. Mauris eu adipiscing ultrices ametodio aenean neque. Fusce ipsum orci rhoncus aliporttitor integer platea placerat.
            </p>
            <div class="flex gap-[32px]">
                <img src="../../assets/apple.svg" alt="appstore">
                <img style="display: inline;" src="../../assets/google.svg" alt="googleplay">
            </div>
            
        </div>
    </section>
</template>

<style scoped>
    #control {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .content {
        max-width: 470px;
    }
    .bill-image {
        width: 530px;
        height: 455px;
    }
    p {
        margin-top: 24px;
        margin-bottom: 49px;
    }
</style>