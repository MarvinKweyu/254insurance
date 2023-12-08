<template>
    <section id="hero-10" class="bg--scroll hero-section">
        <div class="container">
            <div class="row d-flex align-items-center">
                <!-- HERO TEXT -->
                <div class="col-md-6">
                    <div class="hero-10-txt wow fadeInRight">
                        <!-- Title -->
                        <h2 class="s-52 w-700">Keep your files safe with Martex</h2>
                        <!-- Text -->
                        <h4 class="s-28 color--grey">Your content is secure and stays private anywhere, anytime</h4>
                        <!-- Buttons -->
                        <div class="btns-group d-flex justify-content-center">
                            <a href="#banner-13" class="btn r-04 btn--theme hover--black">Get started</a>
                            <ElementsVideoModal :link="'https://www.youtube.com/embed/Pf03RTjeISE'">
                                <template v-slot:button>
                                    <span>See how it works</span>
                                </template>
                            </ElementsVideoModal>
                        </div>
                        <!-- Buttons Text -->
                        <p class="p-sm btns-group-txt">
                            Requires macOS 10.13+ or Windows 10+ 64bit.
                            <span class="txt-data">Current version 2.18.03 <NuxtLink to="/download">What's New?</NuxtLink></span>
                        </p>
                    </div>
                </div>
                <!-- END HERO TEXT -->
                <!-- HERO IMAGE -->
                <div class="col-md-6">
                    <div class="hero-10-img wow fadeInLeft">
                        <img class="img-fluid" src="/assets/images/dashboard-04.png" alt="hero-image" />
                    </div>
                </div>
            </div>
            <!-- End row -->
        </div>
        <!-- End container -->
    </section>
</template>
