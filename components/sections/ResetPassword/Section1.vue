<template>
    <section id="reset-password" class="bg--fixed reset-password-section division">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-md-7 col-lg-5">
                    <!-- LOGO -->
                    <div class="login-page-logo">
                        <img class="img-fluid" src="/assets/images/logo-blue.png" alt="logo-image" />
                    </div>
                    <!-- RESET PASSWORD FORM -->
                    <div class="reset-page-wrapper text-center">
                        <form name="resetpasswordform" class="row reset-password-form r-10">
                            <!-- Title-->
                            <div class="col-md-12">
                                <div class="reset-form-title">
                                    <h5 class="s-26 w-700">Forgot your password?</h5>
                                    <p class="p-sm color--grey">Enter your email address, if an account exists we‘ll send you a link to reset your password.</p>
                                </div>
                            </div>
                            <!-- Form Input -->
                            <div class="col-md-12">
                                <input class="form-control email" type="email" name="email" placeholder="example@example.com" />
                            </div>
                            <!-- Form Submit Button -->
                            <div class="col-md-12">
                                <button type="submit" class="btn btn--theme hover--theme submit">Reset My Password</button>
                            </div>
                            <!-- Form Data  -->
                            <div class="col-md-12">
                                <div class="form-data text-center">
                                    <span><NuxtLink to="/login-1">Never mind, I remembered!</NuxtLink></span>
                                </div>
                            </div>
                            <!-- Form Message -->
                            <div class="col-lg-12 reset-form-msg">
                                <span class="loading"></span>
                            </div>
                        </form>
                    </div>
                    <!-- END RESET PASSWORD FORM -->
                </div>
            </div>
            <!-- End row -->
        </div>
        <!-- End container -->
    </section>
</template>
