<template>
    <section id="hero-27" class="gr--whitesmoke hero-section">
        <div class="hero-overlay bg--fixed">
          
          
 <div class="col text-center brands-carousel-6">
                    <Swiper
                        :modules="[SwiperAutoplay, SwiperEffectCreative]"
                        :slides-per-view="1"
                        :loop="true"
                        :autoplay="{
                            delay: 3000,
                            disableOnInteraction: true
                        }"
                    >
                        <SwiperSlide v-for="image in images" :key="image"
                            ><div class="brand-logo"><img class="img-fluid" :src="image" alt="brand-logo" /></div
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
        "https://plus.unsplash.com/premium_photo-1664301862835-d500277d4bcc?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OXx8aG9zcGl0YWwlMjBiZWR8ZW58MHx8MHx8fDA%3D",
        "https://plus.unsplash.com/premium_photo-1664302397663-e4478130d0f1?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NXx8YWZyaWNhbiUyMG9uJTIwd2hlZWxjaGFpcnxlbnwwfHwwfHx8MA%3D%3D",
        "https://plus.unsplash.com/premium_photo-1664301862835-d500277d4bcc?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OXx8aG9zcGl0YWwlMjBiZWR8ZW58MHx8MHx8fDA%3D",
        "https://images.unsplash.com/photo-1528752477378-485b46bedcde?q=80&w=1933&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
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