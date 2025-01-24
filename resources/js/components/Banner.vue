<template>
    <!-- Banner Section -->
    <section id="banner" class="banner section dark-background">
        <div class="overlay"></div> <!-- Added overlay div -->
        <div class="container">
            <div class="row gy-4">
                <div class="col-lg-6 order-2 order-lg-1 d-flex flex-column justify-content-center" data-aos="zoom-out">
                    <h1>From Idea to Reality</h1>
                    <p>Bringing Your Ideas to Life with Innovative Solutions and Seamless Experiences!</p>
                    <div class="d-flex">
                        <a href="#about" class="btn-get-started">Get Started</a>
                    </div>
                </div>
                <div class="col-lg-6 order-1 order-lg-2 banner-img" data-aos="zoom-out" data-aos-delay="200">
                    <img src="/public/images/gurr-hollow-tilted-logo.png" class="img-fluid animated" alt="gurr-hollow-logo">
                </div>
            </div>
        </div>
    </section><!-- /Banner Section -->
</template>

<style>
.banner {
    background-image: url('/images/banner.png');
}
</style>

<script>
export default {
    name: "Banner"
};
</script>
