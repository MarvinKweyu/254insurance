<template>
    <div id="login" class="bg--scroll login-section division">
        <div class="container">
            <div class="row justify-content-center">
                <!-- REGISTER PAGE WRAPPER -->
                <div class="col-lg-11">
                    <div class="register-page-wrapper r-16 bg--fixed">
                        <div class="row">
                            <!-- LOGIN PAGE TEXT -->
                            <div class="col-md-6">
                                <div class="register-page-txt color--white">
                                    <!-- Logo -->
                                    <img class="img-fluid" src="/assets/images/logo-white.png" alt="logo-image" />
                                    <!-- Title -->
                                    <h2 class="s-42 w-700">Welcome</h2>
                                    <h2 class="s-42 w-700">back to Martex</h2>
                                    <!-- Text -->
                                    <p class="p-md mt-25">Integer congue sagittis and velna augue egestas magna suscipit purus aliquam</p>
                                    <!-- Copyright -->
                                    <div class="register-page-copyright">
                                        <p class="p-sm">&copy; 2023 Martex. <span>All Rights Reserved</span></p>
                                    </div>
                                </div>
                            </div>
                            <!-- END LOGIN PAGE TEXT -->
                            <!-- LOGIN FORM -->
                            <div class="col-md-6">
                                <div class="register-page-form">
                                    <form name="signinform" class="row sign-in-form">
                                        <!-- Google Button -->
                                        <div class="col-md-12">
                                            <a href="#" class="btn btn-google ico-left"> <img src="/assets/images/png_icons/google.png" alt="google-icon" /> Sign in with Google </a>
                                        </div>
                                        <!-- Login Separator -->
                                        <div class="col-md-12 text-center">
                                            <div class="separator-line">Or, sign in with your email</div>
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
                                                <input class="form-control password" type="password" name="password" placeholder="* * * * * * * * *" />
                                            </div>
                                        </div>
                                        <!-- Reset Password Link -->
                                        <div class="col-md-12">
                                            <div class="reset-password-link">
                                                <p class="p-sm"><NuxtLink to="/reset-password" class="color--theme">Forgot your password?</NuxtLink></p>
                                            </div>
                                        </div>
                                        <!-- Form Submit Button -->
                                        <div class="col-md-12">
                                            <button type="submit" class="btn btn--theme hover--theme submit">Log In</button>
                                        </div>
                                        <!-- Sign Up Link -->
                                        <div class="col-md-12">
                                            <p class="create-account text-center">Don't have an account? <NuxtLink to="/signup-2" class="color--theme">Sign up</NuxtLink></p>
                                        </div>
                                    </form>
                                </div>
                            </div>
                            <!-- END LOGIN FORM -->
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
