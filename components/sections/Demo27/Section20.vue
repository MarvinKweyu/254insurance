<template>
    <div id="rating-1" class="pt-70 rating-section d-none">
        <div class="container">
            <!-- RATING TITLE -->
            <div class="row justify-content-center">
                <div class="col-md-10 col-lg-9">
                    <div class="rating-title mb-40">
                        <h5 class="s-18 color--grey w-500">Our clients love us as much as we love them</h5>
                    </div>
                </div>
            </div>
            <!-- RATING-1 WRAPPER -->
            <div class="rating-1-wrapper">
                <div class="row justify-content-md-center row-cols-1 row-cols-md-3">
                    <!-- RATING BOX #1 -->
                    <div class="col">
                        <div id="rb-1-1" class="rbox-1">
                            <!-- Brand Logo -->
                            <div class="rbox-1-img">
                                <img class="img-fluid" src="/assets/images/brand-21.png" alt="feature-image" />
                            </div>
                            <!-- Rating Stars -->
                            <div class="star-rating ico-10 bg--white-100 r-100 clearfix">
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star-half-empty mr-5"></span>
                                &nbsp; 4.7/5
                            </div>
                        </div>
                    </div>
                    <!-- RATING BOX #2 -->
                    <div class="col">
                        <div id="rb-1-2" class="rbox-1">
                            <!-- Brand Logo -->
                            <div class="rbox-1-img">
                                <img class="img-fluid" src="/assets/images/brand-22.png" alt="feature-image" />
                            </div>
                            <!-- Rating Stars -->
                            <div class="star-rating ico-10 bg--white-100 r-100 clearfix">
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star mr-5"></span>
                                &nbsp; 4.95/5
                            </div>
                        </div>
                    </div>
                    <!-- RATING BOX #3 -->
                    <div class="col">
                        <div id="rb-1-3" class="rbox-1">
                            <!-- Brand Logo -->
                            <div class="rbox-1-img">
                                <img class="img-fluid" src="/assets/images/brand-23.png" alt="feature-image" />
                            </div>
                            <!-- Rating Stars -->
                            <div class="star-rating ico-10 bg--white-100 r-100 clearfix">
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star"></span>
                                <span class="flaticon-star-1 mr-5"></span>
                                &nbsp; 4.24/5
                            </div>
                        </div>
                    </div>
                </div>
                <!-- End row -->
            </div>
            <!-- END RATING-1 WRAPPER -->
        </div>
        <!-- End container -->
    </div>
    <!-- END RATING-1 -->
    <!-- BANNER-3
			============================================= -->


    <div class=container>
        <div class="row row-cols-1 row-cols-md-2">
            <div class="col founder-img">
                <img class="img-fluid" src="/assets/images/bilha.jpeg" alt="Bilha Wachira" />
            </div>
            <div class="col ">
                <div class="founder-description">
                    <h6 class="s-20 color--black w-700">Bilha Wachira</h6>
                    <p class="color--grey">Founder and CEO</p>
                    <article>
                    Bilha Wachira is a passionate insurance advisor vastly experienced in the life and health insurance industry.  She has hands on experience and a business acumen spanning well over 15+ years. 
                    Her passion is to see all  families covered for death, illness and injury. Keen on retirement planning education and the importance of growing and protecting generational wealth. 
                </article>

                <div></div>
            </div>
            </div>
        </div>
    </div>
                    
</template>

<style scoped>
.img-fluid{
    width: 60%;
    height: 80%;
    /*  make the image fit within the size */
    object-fit: contain;
}

.founder-img, .founder-description{
 /* center image within the column  */
    display: flex;
    justify-content: center;
    align-items: center;
}
/* .founder-description{
    margin-top: 20%;
} */
</style>
