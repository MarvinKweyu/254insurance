<template>
    <section id="pricing-3" class="gr--whitesmoke pt-100 pricing-section">
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
                            <p class="color--theme">Save up to 25% with yearly billing</p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- END SECTION TITLE -->
            <!-- PRICING TABLES -->
            <div class="pricing-3-wrapper text-center">
                <div class="row row-cols-1 row-cols-md-3">
                    <!-- FREE PLAN -->
                    <div class="col">
                        <div id="pt-3-1" class="p-table pricing-3-table bg--white-100 block-shadow r-12 wow fadeInUp">
                            <!-- TABLE HEADER -->
                            <div class="pricing-table-header">
                                <!-- Title -->
                                <h4 class="s-32">Free</h4>
                                <!-- Text -->
                                <p class="color--grey">For anyone getting started with smaller projects.</p>
                                <!-- Price -->
                                <div class="price mt-25">
                                    <sup class="color--black">$</sup>
                                    <span class="color--black">0</span>
                                    <sup class="validity color--grey">forever</sup>
                                </div>
                            </div>
                            <!-- END TABLE HEADER -->
                            <!-- BUTTON -->
                            <a href="#" class="pt-btn btn btn--theme hover--theme">Get srarted - it's free</a>
                            <p class="p-sm btn-txt color--grey">No credit card required</p>
                        </div>
                    </div>
                    <!-- END FREE PLAN -->
                    <!-- PLUS PLAN -->
                    <div class="col">
                        <div id="pt-3-2" class="p-table pricing-3-table bg--white-100 block-shadow r-12 wow fadeInUp">
                            <!-- TABLE HEADER -->
                            <div class="pricing-table-header">
                                <!-- Title -->
                                <h4 class="s-32">Plus</h4>
                                <!-- Text -->
                                <p class="color--grey">For personal use or small teams with simple workflows.</p>
                                <!-- Price -->
                                <div class="price mt-25">
                                    <!-- Monthly Price -->
                                    <div class="price2" v-if="showPrice2">
                                        <sup class="color--black">$</sup>
                                        <span class="color--black">3</span>
                                        <sup class="coins color--black">99</sup>
                                        <sup class="validity color--grey">per month</sup>
                                    </div>
                                    <!-- Yearly Price -->
                                    <div class="price1" v-if="showPrice1">
                                        <sup class="color--black">$</sup>
                                        <span class="color--black">35</span>
                                        <sup class="coins color--black">99</sup>
                                        <sup class="validity color--grey">per year</sup>
                                    </div>
                                </div>
                            </div>
                            <!-- END TABLE HEADER -->
                            <!-- BUTTON -->
                            <a href="#" class="pt-btn btn btn--theme hover--theme">Start 14-day trial</a>
                            <p class="p-sm btn-txt">7-Day Money Back Guarantee</p>
                        </div>
                    </div>
                    <!-- END PLUS PLAN -->
                    <!-- PRO PLAN -->
                    <div class="col">
                        <div id="pt-3-3" class="p-table pricing-3-table bg--white-100 block-shadow r-12 wow fadeInUp">
                            <!-- TABLE HEADER -->
                            <div class="pricing-table-header">
                                <!-- Title -->
                                <h4 class="s-32">Pro</h4>
                                <!-- Text -->
                                <p class="color--grey">For growing teams that need more services and flexibility.</p>
                                <!-- Price -->
                                <div class="price mt-25">
                                    <!-- Monthly Price -->
                                    <div class="price2" v-if="showPrice2">
                                        <sup class="color--black">$</sup>
                                        <span class="color--black">6</span>
                                        <sup class="coins color--black">99</sup>
                                        <sup class="validity color--grey">per month</sup>
                                    </div>
                                    <!-- Yearly Price -->
                                    <div class="price1" v-if="showPrice1">
                                        <sup class="color--black">$</sup>
                                        <span class="color--black">62</span>
                                        <sup class="coins color--black">99</sup>
                                        <sup class="validity color--grey">per year</sup>
                                    </div>
                                </div>
                            </div>
                            <!-- END TABLE HEADER -->
                            <!-- BUTTON -->
                            <a href="#" class="pt-btn btn btn--theme hover--theme">Upgrade to PRO</a>
                            <p class="p-sm btn-txt">7-Day Money Back Guarantee</p>
                        </div>
                    </div>
                    <!-- END PRO PLAN -->
                </div>
            </div>
            <!-- PRICING TABLES -->
            <!-- PRICING NOTICE TEXT -->
            <div class="row justify-content-center">
                <div class="col-lg-10">
                    <div class="pricing-notice wow fadeInUp">
                        <!-- Text -->
                        <p class="mb-0">The above prices do not include applicable taxes based on your billing address. The final price will be displayed on the checkout page, before the payment is completed</p>
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
