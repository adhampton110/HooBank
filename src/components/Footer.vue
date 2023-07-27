<script setup>
    import {logo,instagram,facebook,twitter,linkedin} from '../assets/';
</script>

<template>
    <section id="footer">
        <div class="site-map">
            <div class="logo">
                <img :src="logo" alt="logo">
                <p>A new way to make the payments easy, reliable and secure</p>
            </div>
            <div class="redirects">
                <div class="useful">
                    <h4>Useful Links</h4>
                    <a href="#">Content</a>
                    <a href="#">How it Works</a>
                    <a href="#">Create</a>
                    <a href="#">Explore</a>
                    <a href="#">Terms & Services</a>
                </div>
                <div class="community">
                    <h4>Community</h4>
                    <a href="#">Help Center</a>
                    <a href="#">Partners</a>
                    <a href="#">Suggestions</a>
                    <a href="#">Blog</a>
                    <a href="#">Newsletters</a>
                </div>
                <div class="partner">
                    <h4>Partner</h4>
                    <a href="#">Our Partner</a>
                    <a href="#">Become a Partner</a>
                </div>
            </div>
        </div>
        <hr>
        <div class="flex justify-between">
            <p>Copyright. 2021HooBank. All Right Reserved</p>
            <div class="socials">
                <img :src="instagram" alt="instagram">
                <img :src="facebook" alt="facebook">
                <img :src="twitter" alt="twitter">
                <img :src="linkedin" alt="linkedin">
            </div>
        </div>
    </section>
</template>

<style scoped>
    #footer {
        background-color: var(--black);
    }
    .site-map {
        display: flex;
        justify-content: space-between;
    }
    .logo {
        max-width: 312px;
    }
    .logo p {
        position: relative;
        left: 30px;
    }
    .redirects {
        display: flex;
        justify-content: space-between;
    }
    .useful,.community,.partner {
        display: flex;
        flex-direction: column;

    }
    .socials {
        display: flex;
        gap: 24px;
    }
</style>