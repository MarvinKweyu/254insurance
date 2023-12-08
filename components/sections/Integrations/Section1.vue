<template>
    <section class="gr--whitesmoke ct-08 inner-page-hero content-section division">
        <div class="container">
            <!-- SECTION TITLE -->
            <div class="row justify-content-center">
                <div class="col-md-10 col-lg-9">
                    <div class="section-title mb-70">
                        <!-- Title -->
                        <h2 class="s-52 w-700">Integrate with your essential tools in few clicks</h2>
                        <!-- Text -->
                        <p class="s-21">Ligula risus auctor tempus magna feugiat lacinia.</p>
                    </div>
                </div>
            </div>
            <!-- IMAGE BLOCK -->
            <div class="row">
                <div class="col">
                    <div class="img-block video-preview wow fadeInUp">
                        <!-- Play Icon -->
                        <ElementsVideoModal :link="'https://www.youtube.com/embed/Pf03RTjeISE'">
                            <template v-slot:button>
                                <div class="video-btn video-btn-xl bg--pink-400 ico-90">
                                    <div class="video-block-wrapper"><span class="flaticon-play-button"></span></div>
                                </div>
                            </template>
                        </ElementsVideoModal>
                        <!-- Preview Image -->
                        <img class="img-fluid" src="/assets/images/dashboard-06.png" alt="video-preview" />
                    </div>
                </div>
            </div>
        </div>
        <!-- End container -->
    </section>
</template>
