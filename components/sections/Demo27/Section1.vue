<template>
    <section id="hero-27" class="gr--whitesmoke hero-section">
        <div class="hero-overlay bg--fixed">
            <div class="container text-center">
                <!-- HERO TEXT -->
                <div class="row justify-content-center">
                    <div class="col-md-10 col-lg-9">
                        <div class="hero-27-txt wow fadeInUp">
                            <!-- Title -->
                            <h2 class="s-60 w-700">The complete toolkit to engage your business</h2>
                            <!-- Text -->
                            <p class="s-20">Mauris donec ociis diam magnis sapien sagittis sapien tempor volute gravida and aliquet tortor aliquet egestas magna</p>
                            <!-- Buttons -->
                            <div class="btns-group d-flex justify-content-center">
                                <a href="#banner-3" class="btn r-04 btn--theme hover--theme">Get started for free</a>
                                <ElementsVideoModal :link="'https://www.youtube.com/embed/Pf03RTjeISE'">
                                    <template v-slot:button>
                                        <span class="video-popup2 btn r-04 btn--theme hover--tra-black ico-20 ico-right">See how it works</span>
                                    </template>
                                </ElementsVideoModal>
                            </div>
                            <!-- Advantages List -->
                            <ul class="advantages ico-15 mt-25 clearfix">
                                <li><p>No credit card required</p></li>
                                <li class="advantages-links-divider">
                                    <p><span class="flaticon-minus"></span></p>
                                </li>
                                <li><p>Cancel at anytime</p></li>
                                <li class="advantages-links-divider">
                                    <p><span class="flaticon-minus"></span></p>
                                </li>
                                <li><p>Free 14 days trial</p></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <!-- END HERO TEXT -->
            </div>
            <!-- End container -->
        </div>
        <!-- End hero-overlay -->
    </section>
</template>
