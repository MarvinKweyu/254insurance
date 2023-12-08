<template>
    <section id="pricing-1" class="gr--whitesmoke py-100 pricing-section">
        <div class="container">
            <!-- SECTION TITLE -->
            <div class="row justify-content-center">
                <div class="col-md-10 col-lg-8">
                    <div class="section-title mb-70">
                        <!-- Title -->
                        <h2 class="s-50 w-700">Simple, Flexible Pricing</h2>
                        <!-- TOGGLE BUTTON -->
                        <div class="toggle-btn ext-toggle-btn toggle-btn-md mt-30">
                            <span class="toggler-txt">Billed monthly</span>
                            <label class="switch-wrap">
                                <input type="checkbox" id="checkbox" @change="togglePrices" />
                                <span class="switcher bg--grey switcher--theme">
                                    <span class="show-annual"></span>
                                    <span class="show-monthly"></span>
                                </span>
                            </label>
                            <span class="toggler-txt">Billed yearly</span>
                            <!-- Text -->
                            <p class="color--theme">Save up to 35% with yearly billing</p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- END SECTION TITLE -->
            <!-- PRICING TABLES -->
            <div class="pricing-1-wrapper">
                <div class="row row-cols-1 row-cols-md-3">
                    <!-- STARTER PLAN -->
                    <div class="col">
                        <div id="pt-1-1" class="p-table pricing-1-table bg--white-100 block-shadow r-12 wow fadeInUp">
                            <!-- TABLE HEADER -->
                            <div class="pricing-table-header">
                                <!-- Title -->
                                <h5 class="s-24 w-700">Starter</h5>
                                <!-- Price -->
                                <div class="price">
                                    <sup class="color--black">$</sup>
                                    <span class="color--black">0</span>
                                    <sup class="validity color--grey">&nbsp;/&ensp;forever</sup>
                                    <p class="color--grey">For professionals getting started with smaller projects.</p>
                                </div>
                                <!-- Button -->
                                <a href="#" class="pt-btn btn r-04 btn--theme hover--theme">Get srarted - it's free</a>
                                <p class="p-sm btn-txt text-center color--grey">No credit card required</p>
                            </div>
                            <!-- END TABLE HEADER -->
                            <!-- PRICING FEATURES -->
                            <ul class="pricing-features color--black ico-10 ico--green mt-25">
                                <li>
                                    <p><span class="flaticon-check"></span> 2 free projects</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> 1 GB of cloud storage</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> For personal use</p>
                                </li>
                                <li class="disabled-option">
                                    <p><span class="flaticon-check"></span> Weekly data backup</p>
                                </li>
                                <li class="disabled-option">
                                    <p><span class="flaticon-check"></span> No Ads. No trackers</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> 12/5 email support</p>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <!-- END STARTER PLAN -->
                    <!-- BASIC PLAN -->
                    <div class="col">
                        <div id="pt-1-2" class="p-table pricing-1-table bg--white-100 block-shadow r-12 wow fadeInUp">
                            <!-- TABLE HEADER -->
                            <div class="pricing-table-header">
                                <!-- Title -->
                                <h5 class="s-24">Basic</h5>
                                <!-- Price -->
                                <div class="price">
                                    <!-- Monthly Price -->
                                    <div class="price2" v-if="showPrice2">
                                        <sup class="color--black">$</sup>
                                        <span class="color--black">16.99</span>
                                        <sup class="validity color--grey">&nbsp;/&ensp;mo</sup>
                                    </div>
                                    <!-- Yearly Price -->
                                    <div class="price1" v-if="showPrice1">
                                        <sup class="color--black">$</sup>
                                        <span class="color--black">142.75</span>
                                        <sup class="validity color--grey">&nbsp;/&ensp;yr</sup>
                                        <!-- Discount Badge -->
                                        <div class="pricing-discount bg--yellow-400 color--black r-36">
                                            <h6 class="s-17">Save 30%</h6>
                                        </div>
                                    </div>
                                    <!-- Text -->
                                    <p class="color--grey">For personal use or small teams with simple workflows.</p>
                                </div>
                                <!-- End Price -->
                                <!-- Button -->
                                <a href="#" class="pt-btn btn r-04 btn--theme hover--theme">Start 14-day trial</a>
                                <p class="p-sm btn-txt text-center color--grey">7-Day Money Back Guarantee</p>
                            </div>
                            <!-- END TABLE HEADER -->
                            <!-- PRICING FEATURES -->
                            <ul class="pricing-features color--black ico-10 ico--green mt-25">
                                <li>
                                    <p><span class="flaticon-check"></span> Up to 250 projects</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> 15 GB of Cloud Storage</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> Shared team workspace</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> Daily data backup</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> No Ads. No trackers</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> 12/7 email support</p>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <!-- END BASIC PLAN -->
                    <!-- ADVANCED PLAN -->
                    <div class="col">
                        <div id="pt-1-3" class="p-table pricing-1-table bg--white-100 block-shadow r-12 wow fadeInUp">
                            <!-- TABLE HEADER -->
                            <div class="pricing-table-header">
                                <!-- Title -->
                                <h5 class="s-24">Advanced</h5>
                                <!-- Price -->
                                <div class="price">
                                    <!-- Monthly Price -->
                                    <div class="price2" v-if="showPrice2">
                                        <sup class="color--black">$</sup>
                                        <span class="color--black">24.99</span>
                                        <sup class="validity color--grey">&nbsp;/&ensp;mo</sup>
                                    </div>
                                    <!-- Yearly Price -->
                                    <div class="price1" v-if="showPrice1">
                                        <sup class="color--black">$</sup>
                                        <span class="color--black">194.99</span>
                                        <sup class="validity color--grey">&nbsp;/&ensp;yr</sup>
                                        <!-- Discount Badge -->
                                        <div class="pricing-discount bg--yellow-400 color--black r-36">
                                            <h6 class="s-17">Save 35%</h6>
                                        </div>
                                    </div>
                                    <!-- Text -->
                                    <p class="color--grey">For growing teams that need more services and flexibility.</p>
                                </div>
                                <!-- End Price -->
                                <!-- Button -->
                                <a href="#" class="pt-btn btn r-04 btn--theme hover--theme">Upgrade your plan</a>
                                <p class="p-sm btn-txt text-center color--grey">7-Day Money Back Guarantee</p>
                            </div>
                            <!-- END TABLE HEADER -->
                            <!-- PRICING FEATURES -->
                            <ul class="pricing-features color--black ico-10 ico--green mt-25">
                                <li>
                                    <p><span class="flaticon-check"></span> Everything in Basic</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> Private cloud hosting</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> Custom security</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> Advanced user permissions</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> Multi-team management</p>
                                </li>
                                <li>
                                    <p><span class="flaticon-check"></span> 24/7 Email Support</p>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <!-- END ADVANCED PLAN -->
                </div>
            </div>
            <!-- PRICING TABLES -->
            <!-- PRICING NOTICE TEXT -->
            <div class="row justify-content-center">
                <div class="col-lg-10">
                    <div class="pricing-notice wow fadeInUp">
                        <!-- Text -->
                        <p>The above prices do not include applicable taxes based on your billing address. The final price will be displayed on the checkout page, before the payment is completed</p>
                    </div>
                </div>
            </div>
        </div>
        <!-- End container -->
    </section>
</template>
<script>
export default {
    data() {
        return {
            showPrice1: false,
            showPrice2: true
        };
    },
    methods: {
        togglePrices() {
            this.showPrice1 = !this.showPrice1;
            this.showPrice2 = !this.showPrice2;
        }
    }
};
</script>
