<template>
    <section id="hero-12" class="bg--scroll hero-section">
        <div class="hero-overlay">
            <div class="container text-center">
                <!-- HERO TEXT -->
                <div class="row justify-content-center">
                    <div class="col-md-10 col-lg-9 col-xl-10">
                        <div class="hero-12-txt color--white wow fadeInUp">
                            <!-- Title -->
                            <h2 class="s-62 w-700">Find inspiration for your next design project</h2>
                            <!-- Text -->
                            <p class="s-22">Pixel-perfect, lovely design. More power behind every pixel</p>
                            <!-- Button -->
                            <a href="#banner-13" class="btn r-04 btn--theme hover--tra-white">Get started for free</a>
                            <p class="p-sm btn-txt ico-15"><span class="flaticon-check"></span> No credit card needed, free 14-day trial</p>
                        </div>
                    </div>
                </div>
                <!-- END HERO TEXT -->
                <!-- HERO IMAGE -->
                <div class="row">
                    <div class="col">
                        <div class="hero-12-img video-preview wow fadeInUp">
                            <!-- Play Icon -->
                            <ElementsVideoModal :link="'https://www.youtube.com/embed/GcMiYI1gWD4'">
                                <template v-slot:button>
                                    <div class="video-btn video-btn-xl bg--pink-400 ico-90">
                                        <div class="video-block-wrapper"><span class="flaticon-play-button"></span></div>
                                    </div>
                                </template>
                            </ElementsVideoModal>
                            <!-- Preview Image -->
                            <img class="img-fluid" src="/assets/images/dashboard-04.png" alt="hero-image" />
                        </div>
                    </div>
                </div>
                <!-- END HERO IMAGE -->
            </div>
            <!-- End container -->
        </div>
        <!-- End hero-overlay -->
    </section>
</template>
