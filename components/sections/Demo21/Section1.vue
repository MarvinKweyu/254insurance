<template>
    <section id="hero-21" class="hero-section">
        <div class="container text-center">
            <!-- HERO TEXT -->
            <div class="row justify-content-center">
                <div class="col-md-10 col-lg-9">
                    <div class="hero-21-txt wow fadeInUp">
                        <!-- Title -->
                        <h2 class="s-56 w-700">The perfect analytics tool for your online business</h2>
                        <!-- Buttons -->
                        <div class="btns-group">
                            <a href="#banner-13" class="btn r-04 btn--theme hover--theme">Get started for free</a>
                            <a href="#features-5" class="btn r-04 btn--tra-black hover--theme">How it works</a>
                        </div>
                        <!-- Advantages List -->
                        <ul class="advantages ico-15 mt-15 clearfix">
                            <li><p class="p-sm">No credit card required</p></li>
                            <li class="advantages-links-divider">
                                <p><span class="flaticon-minus"></span></p>
                            </li>
                            <li><p class="p-sm">Free 30 days trial</p></li>
                        </ul>
                    </div>
                </div>
            </div>
            <!-- END HERO TEXT -->
            <!-- HERO IMAGE -->
            <div class="hero-21-wrapper r-34">
                <div class="hero-overlay bg--fixed">
                    <div class="row">
                        <div class="col">
                            <div class="hero-21-img video-preview wow fadeInUp">
                                <!-- Play Icon -->
                                <ElementsVideoModal :link="'https://www.youtube.com/embed/GcMiYI1gWD4'">
                                    <template v-slot:button>
                                        <div class="video-btn video-btn-xl bg--pink-400 ico-90">
                                            <div class="video-block-wrapper"><span class="flaticon-play-button"></span></div>
                                        </div>
                                    </template>
                                </ElementsVideoModal>
                                <!-- Preview Image -->
                                <img class="img-fluid" src="/assets/images/tablet-01.png" alt="video-preview" />
                            </div>
                        </div>
                    </div>
                </div>
                <!-- hero overlay -->
            </div>
            <!-- End hero-21-wrapper -->
        </div>
        <!-- End container -->
    </section>
</template>
