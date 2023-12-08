<template>
    <footer id="footer-3" class="pt-100 footer ft-3-ntr">
        <div class="container">
            <!-- FOOTER CONTENT -->
            <div class="row">
                <!-- FOOTER LOGO -->
                <div class="col-xl-3">
                    <div class="footer-info">
                        <img class="footer-logo" src="/assets/images/logo-pink.png" alt="footer-logo" />
                    </div>
                </div>
                <!-- FOOTER LINKS -->
                <div class="col-sm-4 col-lg-3 col-xl-2">
                    <div class="footer-links fl-1">
                        <!-- Title -->
                        <h6 class="s-17 w-700">Company</h6>
                        <!-- Links -->
                        <ul class="foo-links clearfix">
                            <li>
                                <p><NuxtLink to="/about">About Us</NuxtLink></p>
                            </li>
                            <li>
                                <p><NuxtLink to="/blog-listing">About Us</NuxtLink></p>
                            </li>
                            <li>
                                <p><NuxtLink to="/reviews">Customers</NuxtLink></p>
                            </li>
                            <li>
                                <p><a href="#">Community</a></p>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- END FOOTER LINKS -->
                <!-- FOOTER LINKS -->
                <div class="col-sm-4 col-lg-2">
                    <div class="footer-links fl-2">
                        <!-- Title -->
                        <h6 class="s-17 w-700">Product</h6>
                        <!-- Links -->
                        <ul class="foo-links clearfix">
                            <li>
                                <p><NuxtLink to="/features">Integration</NuxtLink></p>
                            </li>
                            <li>
                                <p><NuxtLink to="/download">What's New</NuxtLink></p>
                            </li>
                            <li>
                                <p><NuxtLink to="/pricing-1">Pricing</NuxtLink></p>
                            </li>
                            <li>
                                <p><NuxtLink to="/help-center">Help Center</NuxtLink></p>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- END FOOTER LINKS -->
                <!-- FOOTER LINKS -->
                <div class="col-sm-4 col-lg-3 col-xl-2">
                    <div class="footer-links fl-3">
                        <!-- Title -->
                        <h6 class="s-17 w-700">Legal</h6>
                        <!-- Links -->
                        <ul class="foo-links clearfix">
                            <li>
                                <p><NuxtLink to="/terms">Terms of Use</NuxtLink></p>
                            </li>
                            <li>
                                <p><NuxtLink to="/privacy">Privacy Policy</NuxtLink></p>
                            </li>
                            <li>
                                <p><NuxtLink to="/cookies">Cookie Policy</NuxtLink></p>
                            </li>
                            <li>
                                <p><NuxtLink to="/cookies">Site Map</NuxtLink></p>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- END FOOTER LINKS -->
                <!-- FOOTER NEWSLETTER FORM -->
                <div class="col-sm-10 col-md-8 col-lg-4 col-xl-3">
                    <div class="footer-form">
                        <!-- Title -->
                        <h6 class="s-17 w-700">Follow the Best</h6>
                        <!-- Newsletter Form Input -->
                        <form class="newsletter-form">
                            <div class="input-group r-06">
                                <input type="email" class="form-control" placeholder="Email Address" required id="s-email" />
                                <span class="input-group-btn ico-15">
                                    <button type="submit" class="btn color--theme">
                                        <span class="flaticon-right-arrow-1"></span>
                                    </button>
                                </span>
                            </div>
                            <!-- Newsletter Form Notification -->
                            <label for="s-email" class="form-notification"></label>
                        </form>
                    </div>
                </div>
                <!-- END FOOTER NEWSLETTER FORM -->
            </div>
            <!-- END FOOTER CONTENT -->
            <hr />
            <!-- FOOTER DIVIDER LINE -->
            <!-- BOTTOM FOOTER -->
            <div class="bottom-footer">
                <div class="row row-cols-1 row-cols-md-2 d-flex align-items-center">
                    <!-- FOOTER COPYRIGHT -->
                    <div class="col">
                        <div class="footer-copyright">
                            <p class="p-sm">&copy; 2023 Martex. <span>All Rights Reserved</span></p>
                        </div>
                    </div>
                    <!-- FOOTER SOCIALS -->
                    <div class="col">
                        <ul class="bottom-footer-socials ico-20 text-end">
                            <li>
                                <a href="#"><span class="flaticon-facebook"></span></a>
                            </li>
                            <li>
                                <a href="#"><span class="flaticon-twitter"></span></a>
                            </li>
                            <li>
                                <a href="#"><span class="flaticon-instagram"></span></a>
                            </li>
                            <li>
                                <a href="#"><span class="flaticon-youtube"></span></a>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- End row -->
            </div>
            <!-- END BOTTOM FOOTER -->
        </div>
        <!-- End container -->
        <FooterGoToTop />
    </footer>
</template>
