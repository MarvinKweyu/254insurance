<template>
    <section class="bg--04 bg--fixed py-100 ct-01 content-section division">
        <div class="container">
            <div class="row d-flex align-items-center">
                <!-- TEXT BLOCK -->
                <div class="col-md-6 order-last order-md-2">
                    <div class="txt-block left-column wow fadeInRight">
                        <!-- Section ID -->
                        <span class="section-id">Co-founder at Martex</span>
                        <!-- Title -->
                        <h2 class="s-50 w-700">Henry Adams</h2>
                        <!-- Text -->
                        <p class="p-lg">&quot;Sodales tempor sapien diam purus ipsum quaerat and volute fusce a congue laoreet turpis neque diam auctor turpis vitae dolor magna luctus placerat neque ipsum fusce cursus ligula cursus purus vitae purus and ipsum suscipit. Nemo ipsam cubilia donec turpis undo egestas ipsum a purus sapien ultrice aliquam lacus and quaerat an ipsum augue turpis sapien cursus congue augue&quot;</p>
                    </div>
                </div>
                <!-- END TEXT BLOCK -->
                <!-- IMAGE BLOCK -->
                <div class="col-md-6 order-first order-md-2">
                    <div class="img-block j-img video-preview right-column wow fadeInLeft">
                        <!-- Play Icon -->
                        <ElementsVideoModal :link="'https://www.youtube.com/embed/GcMiYI1gWD4'">
                            <template v-slot:button>
                                <div class="video-btn video-btn-xl bg--theme">
                                    <div class="video-block-wrapper"><span class="flaticon-play-button"></span></div>
                                </div>
                            </template>
                        </ElementsVideoModal>
                        <!-- Preview Image -->
                        <img class="img-fluid r-20" src="/assets/images/img-17.jpg" alt="video-preview" />
                    </div>
                </div>
            </div>
            <!-- End row -->
        </div>
        <!-- End container -->
    </section>
</template>
