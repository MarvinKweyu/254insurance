<template>
    <section id="hero-4" class="bg--scroll hero-section">
        <div class="container text-center">
            <!-- HERO TEXT -->
            <div class="row justify-content-center">
                <div class="col-md-10 col-lg-9 col-xl-10">
                    <div class="hero-4-txt wow fadeInUp">
                        <!-- Title -->
                        <h2 class="s-56 w-700">Manage all your content in easy way with Martex</h2>
                        <!-- Buttons -->
                        <div class="btns-group mt-15">
                            <a href="#" class="btn r-04 btn--theme hover--black">Download for MacOS</a>
                            <a href="#" class="btn r-04 btn--tra-black hover--black">Download for Windows</a>
                        </div>
                        <!-- Buttons Group Text -->
                        <p class="p-sm btns-group-txt color--black">
                            Requires macOS 10.13+ or Windows 10+ 64bit.
                            <span class="txt-data">Current version 2.18.03 <NuxtLink to="/download">What's New?</NuxtLink></span>
                        </p>
                    </div>
                </div>
            </div>
            <!-- END HERO TEXT -->
            <!-- HERO IMAGE -->
            <div class="row">
                <div class="col">
                    <div class="hero-4-img video-preview wow fadeInUp">
                        <!-- Play Icon -->
                        <ElementsVideoModal :link="'https://www.youtube.com/embed/GcMiYI1gWD4'">
                            <template v-slot:button>
                                <div class="video-btn video-btn-xl bg--pink-400 ico-90">
                                    <div class="video-block-wrapper"><span class="flaticon-play-button"></span></div>
                                </div>
                            </template>
                        </ElementsVideoModal>
                        <!-- Preview Image -->
                        <img class="img-fluid" src="/assets/images/dashboard-04.png" alt="video-preview" />
                    </div>
                </div>
            </div>
            <!-- END HERO IMAGE -->
        </div>
        <!-- End container -->
    </section>
</template>
