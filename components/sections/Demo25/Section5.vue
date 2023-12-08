<template>
    <section id="lnk-2" class="pt-100 ws-wrapper content-section">
        <div class="container">
            <div class="bc-5-wrapper bg--04 hidd bg--scroll r-16">
                <div class="section-overlay">
                    <!-- SECTION TITLE -->
                    <div class="row justify-content-center">
                        <div class="col-md-11 col-lg-9">
                            <div class="section-title wow fadeInUp mb-60">
                                <!-- Title -->
                                <h2 class="s-48 w-700">Build a customer-centric marketing strategy</h2>
                                <!-- Text -->
                                <p class="p-xl">Aliquam a augue suscipit luctus neque purus ipsum neque diam dolor primis libero tempus, blandit and cursus varius and magnis sodales</p>
                            </div>
                        </div>
                    </div>
                    <!-- IMAGE BLOCK -->
                    <div class="row justify-content-center">
                        <div class="col">
                            <div class="bc-5-img bc-5-tablet img-block-hidden video-preview wow fadeInUp">
                                <!-- Play Icon -->
                                <ElementsVideoModal :link="'https://www.youtube.com/embed/GcMiYI1gWD4'">
                                    <template v-slot:button>
                                        <div class="video-btn video-btn-xl bg--pink-400 ico-90">
                                            <div class="video-block-wrapper"><span class="flaticon-play-button"></span></div>
                                        </div>
                                    </template>
                                </ElementsVideoModal>
                                <!-- Preview Image -->
                                <img class="img-fluid" src="/assets/images/tablet-01.png" alt="content-image" />
                            </div>
                        </div>
                    </div>
                </div>
                <!-- End section overlay -->
            </div>
            <!-- End content wrapper -->
        </div>
        <!-- End container -->
    </section>
</template>
