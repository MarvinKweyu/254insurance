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
                            <!-- 254Insurance: Safeguarding Lives, Ensuring Peace – Your Trusted Partner in Health and Life Insurance. -->
                            <h2 class="s-50 w-700">
                                Welcome to 254 Insurance
                            </h2>
                            <!-- Text -->
                            <p class="s-20">
                                Demistifying Life and Health Insurance.
                            </p>

                             <article class="mt-25">
                                    We simplify your life and health choices by connecting you with the perfect insurance plan tailored to your needs and budget. Our options include individual, family, group health, Medicare, dental, and vision plans.
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
        "https://res.cloudinary.com/dlxhllkxl/image/upload/v1702224214/client-work/last-will_wmt9jr.jpg",
        "https://res.cloudinary.com/dlxhllkxl/image/upload/v1702224214/client-work/hostpital_svyxnw.jpg",
        "https://res.cloudinary.com/dlxhllkxl/image/upload/v1702224960/client-work/life-insurance_gu2sxe.webp",

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