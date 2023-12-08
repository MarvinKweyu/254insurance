<template>
    <div id="signup" class="bg--fixed signup-1 login-section division">
        <div class="container">
            <div class="row">
                <div class="col-md-8 col-lg-6 offset-md-2 offset-lg-3">
                    <div class="register-page-form">
                        <!-- TITLE -->
                        <div class="col-md-12">
                            <div class="register-form-title">
                                <h3 class="s-32 w-700">Create Account</h3>
                                <p class="p-md">Already have an account? <NuxtLink to="/login-1" class="color--theme">Log In</NuxtLink></p>
                            </div>
                        </div>
                        <!-- SIGN UP FORM -->
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
                        </form>
                        <!-- END SIGN UP FORM -->
                    </div>
                </div>
            </div>
            <!-- End row -->
        </div>
        <!-- End container -->
    </div>
</template>
