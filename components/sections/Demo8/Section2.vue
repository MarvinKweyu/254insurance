<template>
    <div id="brands-1" class="pt-80 pb-90 bottom-border brands-section">
        <div class="container">
            <!-- BRANDS CAROUSEL -->
            <div class="row">
                <div class="col text-center">
                    <div class="brands-carousel-6">
                        <Swiper
                            :modules="[SwiperAutoplay, SwiperEffectCreative]"
                            :slides-per-view="6"
                            :loop="true"
                            :autoplay="{
                                delay: 8000,
                                disableOnInteraction: true
                            }"
                        >
                            <SwiperSlide
                                ><div class="brand-logo">
                                    <img class="img-fluid" src="/assets/images/brand-1.png" alt="brand-logo" /></div
                            ></SwiperSlide>
                            <SwiperSlide
                                ><div class="brand-logo">
                                    <img class="img-fluid" src="/assets/images/brand-2.png" alt="brand-logo" /></div
                            ></SwiperSlide>
                            <SwiperSlide
                                ><div class="brand-logo">
                                    <img class="img-fluid" src="/assets/images/brand-3.png" alt="brand-logo" /></div
                            ></SwiperSlide>
                            <SwiperSlide
                                ><div class="brand-logo">
                                    <img class="img-fluid" src="/assets/images/brand-4.png" alt="brand-logo" /></div
                            ></SwiperSlide>
                            <SwiperSlide
                                ><div class="brand-logo">
                                    <img class="img-fluid" src="/assets/images/brand-5.png" alt="brand-logo" /></div
                            ></SwiperSlide>
                            <SwiperSlide
                                ><div class="brand-logo">
                                    <img class="img-fluid" src="/assets/images/brand-6.png" alt="brand-logo" /></div
                            ></SwiperSlide>
                            <SwiperSlide
                                ><div class="brand-logo">
                                    <img class="img-fluid" src="/assets/images/brand-7.png" alt="brand-logo" /></div
                            ></SwiperSlide>
                            <SwiperSlide
                                ><div class="brand-logo">
                                    <img class="img-fluid" src="/assets/images/brand-8.png" alt="brand-logo" /></div
                            ></SwiperSlide>
                            <SwiperSlide
                                ><div class="brand-logo">
                                    <img class="img-fluid" src="/assets/images/brand-9.png" alt="brand-logo" /></div
                            ></SwiperSlide>
                        </Swiper>
                    </div>
                </div>
            </div>
            <!-- END BRANDS CAROUSEL -->
        </div>
        <!-- End container -->
    </div>
</template>
