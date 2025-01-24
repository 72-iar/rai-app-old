Here’s your code with proper tab spacing:

```vue
<template>
    <!-- Services Section -->
    <section id="services" class="services section light-background">

        <!-- Section Title -->
        <div class="container section-title" data-aos="fade-up">
            <h2>Services</h2>
            <p>Offering tailored solutions to meet your goals.</p>
        </div><!-- End Section Title -->

        <div class="container">
            <div class="row gy-4">
                <div class="col-xl-4 col-md-6 d-flex" data-aos="fade-up" data-aos-delay="100">
                    <div class="service-item position-relative">
                        <div class="icon">
                            <img src="/public/images/web-development.png" alt="" width="80">
                        </div>
                        <h4><a href="" class="stretched-link">Web Development</a></h4>
                        <p>Build modern, responsive websites tailored to your business needs.</p>
                    </div>
                </div><!-- End Service Item -->

                <div class="col-xl-4 col-md-6 d-flex" data-aos="fade-up" data-aos-delay="200">
                    <div class="service-item position-relative">
                        <div class="icon">
                            <img src="/public/images/mobile-development.png" alt="" width="80">
                        </div>
                        <h4><a href="" class="stretched-link">Mobile Development</a></h4>
                        <p>Create intuitive mobile apps that deliver seamless user experiences.</p>
                    </div>
                </div><!-- End Service Item -->

                <div class="col-xl-4 col-md-6 d-flex" data-aos="fade-up" data-aos-delay="300">
                    <div class="service-item position-relative">
                        <div class="icon">
                            <img src="/public/images/project-management.png" alt="" width="80">
                        </div>
                        <h4><a href="" class="stretched-link">Project Management</a></h4>
                        <p>Efficiently manage projects to ensure timely delivery and quality results.</p>
                    </div>
                </div><!-- End Service Item -->
            </div>
        </div>

    </section><!-- /Services Section -->
</template>

<script>
export default {
    name: "Services"
};
</script>
```