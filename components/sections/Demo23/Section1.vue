<template>
    <section id="hero-23" class="bg--scroll hero-section">
        <div class="container text-center">
            <!-- HERO TEXT -->
            <div class="row justify-content-center">
                <div class="col-md-10 col-lg-9 col-xl-10">
                    <div class="hero-23-txt wow fadeInUp">
                        <!-- Hero Logo  -->
                        <div class="hero-square-logo">
                            <img class="img-fluid" src="/assets/images/square-logo.png" alt="hero-logo" />
                        </div>
                        <!-- Title -->
                        <h2 class="s-58 w-700">Generate <span class="color--theme">more leads</span> with social media marketing</h2>
                        <!-- Text -->
                        <p class="p-xl">
                            Mauris donec ociis diam magnis sapien sagittis sapien tempor volute gravida <span class="color--black">aliquet tortor undo aliquet an egestas</span>
                            in magna egestas sapien quaerat
                        </p>
                    </div>
                </div>
            </div>
            <!--END HERO TEXT -->
            <!-- HERO IMAGE -->
            <div class="row">
                <div class="col">
                    <div class="hero-23-img video-preview wow fadeInUp">
                        <!-- Play Icon -->
                        <ElementsVideoModal :link="'https://www.youtube.com/embed/GcMiYI1gWD4'">
                            <template v-slot:button>
                                <div class="video-btn video-btn-xl bg--pink-400 ico-90">
                                    <div class="video-block-wrapper"><span class="flaticon-play-button"></span></div>
                                </div>
                            </template>
                        </ElementsVideoModal>
                        <!-- Preview Image -->
                        <img class="img-fluid" src="/assets/images/dashboard-03.png" alt="video-preview" />
                    </div>
                </div>
            </div>
            <!-- END HERO IMAGE -->
        </div>
        <!-- End container -->
        <!-- WAVE SHAPE BOTTOM -->
        <div class="wave-shape-bottom">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill-opacity="1" d="M0,128L80,149.3C160,171,320,213,480,240C640,267,800,277,960,277.3C1120,277,1280,267,1360,261.3L1440,256L1440,320L1360,320C1280,320,1120,320,960,320C800,320,640,320,480,320C320,320,160,320,80,320L0,320Z"></path></svg>
        </div>
    </section>
</template>
