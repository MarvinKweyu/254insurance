<template>
    <div id="signup" class="bg--scroll login-section division">
        <div class="container">
            <div class="row justify-content-center">
                <!-- REGISTER PAGE WRAPPER -->
                <div class="col-lg-11">
                    <div class="register-page-wrapper r-16 bg--fixed">
                        <div class="row">
                            <!-- SIGN UP FORM -->
                            <div class="col-md-6">
                                <div class="register-page-form">
                                    <form name="signupform" class="row sign-up-form">
                                        <!-- Google Button -->
                                        <div class="col-md-12">
                                            <a href="#" class="btn btn-google ico-left"> <img src="/assets/images/png_icons/google.png" alt="google-icon" /> Sign up with Google </a>
                                        </div>
                                        <!-- Login Separator -->
                                        <div class="col-md-12 text-center">
                                            <div class="separator-line">Or, sign up with your email</div>
                                        </div>
                                        <!-- Form Input -->
                                        <div class="col-md-12">
                                            <p class="p-sm input-header">Full name</p>
                                            <input class="form-control name" type="text" name="name" placeholder="John Doe" />
                                        </div>
                                        <!-- Form Input -->
                                        <div class="col-md-12">
                                            <p class="p-sm input-header">Email address</p>
                                            <input class="form-control email" type="email" name="email" placeholder="example@example.com" />
                                        </div>
                                        <!-- Form Input -->
                                        <div class="col-md-12">
                                            <p class="p-sm input-header">Password</p>
                                            <div class="wrap-input">
                                                <span class="btn-show-pass ico-20"><span class="flaticon-visibility eye-pass"></span></span>
                                                <input class="form-control password" type="password" name="password" placeholder="min 8 characters" />
                                            </div>
                                        </div>
                                        <!-- Checkbox -->
                                        <div class="col-md-12">
                                            <div class="form-data">
                                                <span
                                                    >By clicking “Create Account”, you agree to our <NuxtLink to="/terms">Terms</NuxtLink> and that you have read our
                                                    <NuxtLink to="/privacy"> Privacy Policy</NuxtLink>
                                                </span>
                                            </div>
                                        </div>
                                        <!-- Form Submit Button -->
                                        <div class="col-md-12">
                                            <button type="submit" class="btn btn--theme hover--theme submit">Create Account</button>
                                        </div>
                                        <!-- Log In Link -->
                                        <div class="col-md-12">
                                            <p class="create-account text-center">Already have an account? <a href="login-2" class="color--theme">Log in</a></p>
                                        </div>
                                    </form>
                                </div>
                            </div>
                            <!-- END SIGN UP FORM -->
                            <!-- SIGN UP PAGE TEXT -->
                            <div class="col-md-6">
                                <div class="register-page-txt color--white">
                                    <!-- Section ID -->
                                    <span class="section-id">Start for free</span>
                                    <!-- Title -->
                                    <h2 class="s-48 w-700">Create</h2>
                                    <h2 class="s-48 w-700">an account</h2>
                                    <!-- Text -->
                                    <p class="p-md mt-25">Integer congue sagittis and velna augue egestas magna suscipit purus aliquam</p>
                                    <!-- Copyright -->
                                    <div class="register-page-copyright">
                                        <p class="p-sm">&copy; 2023 Martex. <span>All Rights Reserved</span></p>
                                    </div>
                                </div>
                            </div>
                            <!-- END SIGN UP PAGE TEXT -->
                        </div>
                        <!-- End row -->
                    </div>
                    <!-- End register-page-wrapper -->
                </div>
                <!-- END REGISTER PAGE WRAPPER -->
            </div>
            <!-- End row -->
        </div>
        <!-- End container -->
    </div>
</template>
