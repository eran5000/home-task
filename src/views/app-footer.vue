<template>
    <section class="app-footer">
        <div class="logo">
            <img src="../assets/images/logo.svg" alt="">
        </div>
        <div class="connect flex row">
            <div class="item flex row">
                <img src="../assets/images/icon-location.svg" alt="">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</p>
            </div>
            <div class="item flex column">
                <div class="flex row">
                    <img src="../assets/images/icon-phone.svg" alt="">
                    <p>+1-543-123-4567</p>
                </div>
                <div class="flex row">
                    <img src="../assets/images/icon-email.svg" alt="">
                    <p>example@fylo.com</p>
                </div>
            </div>
            <div class="item flex column">
                <p>About Us</p>
                <p>Jobs</p>
                <p>Press</p>
                <p>Blog</p>
            </div>
            <div class="item flex column">
                <p>Contacy Us</p>
                <p>Terms</p>
                <p>Privacy</p>
            </div>
            <div class="logos flex row">
                <font-awesome-icon icon="fa-brands fa-facebook" />
            </div>
        </div>
    </section>
</template>
<script>

export default {
    name: 'app-footer',
    props: {
    }
}
</script>
