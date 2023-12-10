<template>
    <section id="hero-27" class="gr--whitesmoke hero-section">
        <div class="hero-overlay bg--fixed">
          
          
 <div class="col text-center brands-carousel-6">
                    <Swiper
                        :modules="[SwiperAutoplay, SwiperEffectCreative]"
                        :slides-per-view="6"
                        :loop="true"
                        :autoplay="{
                            delay: 8000,
                            disableOnInteraction: true
                        }"
                    >
                        <SwiperSlide v-for="image in images" :key="image"
                            ><div class="brand-logo"><img class="img-fluid" src="https://plus.unsplash.com/premium_photo-1664301862835-d500277d4bcc?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OXx8aG9zcGl0YWwlMjBiZWR8ZW58MHx8MHx8fDA%3D" alt="brand-logo" /></div
                        ></SwiperSlide>
                    
                    </Swiper>
                </div>
            <!-- End container -->
        </div>
            <div class="container text-center">
                <!-- HERO TEXT -->
                <div class="row justify-content-center">
                    <div class="col-md-10 col-lg-9">
                        <div class="hero-27-txt wow fadeInUp">
                            <!-- Title -->
                            <!-- 254Insurance: Safeguarding Lives, Ensuring Peace – Your Trusted Partner in Health and Death Insurance. -->
                            <h2 class="s-50 w-700">
                                Welcome to 254 Insurance
                            </h2>
                            <!-- Text -->
                            <p class="s-20">
                                Demistifying Life and Health Insurance.
                            </p>

                             <article class="mt-25">
                                    We will help you simplify your life and health plan choices and connect you with the right insurance plan that meets your needs and budget. We also offer individual, family  , group health, medicare along with dental and vision plans.
                                </article>
                            <!-- Buttons -->
                          
                       
                        </div>
                    </div>
                </div>
                <!-- END HERO TEXT -->
            </div>

        <!-- End hero-overlay -->
    </section>
</template>

<script>
export default {
  data() {
    return {
      images: [
        "/assets/images/brand-1.png",
        "/assets/images/brand-2.png",
        "/assets/images/brand-3.png",
        "/assets/images/brand-4.png",
        "/assets/images/brand-5.png",
        "/assets/images/brand-6.png",
        "/assets/images/brand-7.png",
        "/assets/images/brand-8.png",
        "/assets/images/brand-9.png"
      ],
      swiperOption: {
        slidesPerView: 6,
        spaceBetween: 30,
        loop: true,
        autoplay: {
          delay: 8000,
          disableOnInteraction: true
        },
        pagination: {
          el: ".swiper-pagination",
          clickable: true
        },
        navigation: {
          nextEl: ".swiper-button-next",
          prevEl: ".swiper-button-prev"
        }
      }
    };
  }
}
</script>