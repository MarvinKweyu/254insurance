<template>
    <section id="hero-16" class="bg--scroll hero-section">
        <div class="container text-center">
            <!-- HERO TEXT -->
            <div class="row justify-content-center">
                <div class="col-md-10 col-lg-9">
                    <div class="hero-16-txt wow fadeInUp">
                        <!-- Title -->
                        <h2 class="s-58 w-700">Easy and secure access to all your files anytime</h2>
                        <!-- Text -->
                        <p class="p-xl">Mauris donec ociis diam magnis sapien sagittis sapien tempor volute gravida and aliquet tortor undo aliquet quaerat in magna egestas sapien quaerat</p>
                        <!-- Button -->
                        <ElementsVideoModal :link="'https://www.youtube.com/embed/Pf03RTjeISE'">
                            <template v-slot:button>
                                <span class="video-popup2 btn r-04 btn--theme hover--tra-black ico-20 ico-right">See how it works</span>
                            </template>
                        </ElementsVideoModal>
                        <p class="p-sm btn-txt ico-15"><span class="flaticon-check"></span> No credit card needed, free 14-day trial</p>
                    </div>
                </div>
            </div>
            <!-- END HERO TEXT -->
            <!-- HERO IMAGE -->
            <div class="row">
                <div class="col">
                    <div class="hero-16-img wow fadeInUp">
                        <img class="img-fluid" src="/assets/images/img-15.png" alt="hero-image" />
                    </div>
                </div>
            </div>
            <!-- END HERO IMAGE -->
        </div>
        <!-- End container -->
        <!-- WAVE SHAPE BOTTOM -->
        <div class="wave-shape-bottom">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 135"><path fill-opacity="1" d="M0,64L120,80C240,96,480,128,720,128C960,128,1200,96,1320,80L1440,64L1440,320L1320,320C1200,320,960,320,720,320C480,320,240,320,120,320L0,320Z"></path></svg>
        </div>
    </section>
</template>
