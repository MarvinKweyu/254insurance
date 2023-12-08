<template>
    <section id="hero-19" class="blur--purple gr--ghost hero-section">
        <div class="container text-center">
            <!-- HERO TEXT -->
            <div class="row justify-content-center">
                <div class="col-md-10 col-lg-9">
                    <div class="hero-19-txt">
                        <!-- Title -->
                        <h2 class="s-56 w-700">Place your business at the top of search engines</h2>
                        <!-- Text -->
                        <p class="p-xl">Mauris donec ociis diam magnis sapien sagittis sapien tempor volute gravida and aliquet tortor undo aliquet quaerat</p>
                        <!-- Buttons -->
                        <div class="btns-group d-flex justify-content-center">
                            <a href="#banner-7" class="btn r-04 btn--theme hover--theme">Get started for free</a>
                            <ElementsVideoModal :link="'https://www.youtube.com/embed/Pf03RTjeISE'">
                                <template v-slot:button>
                                    <span class="video-popup2 btn r-04 btn--theme hover--tra-black ico-20 ico-right">See how it works</span>
                                </template>
                            </ElementsVideoModal>
                        </div>
                    </div>
                </div>
            </div>
            <!-- END HERO TEXT -->
            <!-- BRANDS CAROUSEL -->
            <div id="brands-1" class="py-90">
                <div class="row">
                    <div class="col text-center">
                        <SlidersBrandLogos />
                    </div>
                </div>
                <!-- End row -->
            </div>
            <!-- END BRANDS CAROUSEL -->
            <!-- HERO IMAGE -->
            <div class="row">
                <div class="col">
                    <div class="hero-19-img wow fadeInUp">
                        <img class="img-fluid" src="/assets/images/dashboard-09.png" alt="hero-image" />
                    </div>
                </div>
            </div>
            <!-- END HERO IMAGE -->
        </div>
        <!-- End container -->
    </section>
</template>
