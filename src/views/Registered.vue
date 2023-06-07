<template>
    <section class="section section-shaped section-lg my-0" style="height: 100vH;">
        <div class="shape shape-style-1" style="background: url('img/brand/portal.jpg'); background-repeat: no-repeat; background-size: cover;">
        </div>
        <h1 style="font-size:10em; rotate: -2deg; text-align: center; font-weight:900; color:#fff; line-height:1em;">Steak<br>it easy!</h1>
        <div class="herobtnone" style="width: 100%; display: grid; grid-template-columns: 1fr 1fr; grid-gap: 4em; position:absolute; bottom:3em;">
        <div style="display: inline-grid; justify-content:end;">
        
        
        <button class="btn btn-3 btn-icon btn-primary">
        <base-button tag="a"
        href="#/testing/"
        style="color:#fff;"
        type="info"
        icon="fa fa-code">Join the style
        </base-button>
         </button></div>
        <div style="display: inline-grid; justify-content:start;">
        <button class="btn btn-3 btn-icon btn-primary" style="padding:6px 25px; width:max-content;">Join the adventure</button></div>
        </div>
        <!-- <div class="container pt-lg-md">
            <div class="row justify-content-center">
                <div class="col-lg-5">
                    <card type="secondary" shadow
                          header-classes="bg-white pb-5"
                          body-classes="px-lg-5 py-lg-5"
                          class="border-0">
                        <template>
                            <div class="text-muted text-center mb-3">
                                <small>Sign in with</small>
                            </div>
                            <div class="btn-wrapper text-center">
                                <base-button type="neutral">
                                    <img slot="icon" src="img/icons/common/github.svg">
                                    Github
                                </base-button>

                                <base-button type="neutral">
                                    <img slot="icon" src="img/icons/common/google.svg">
                                    Google
                                </base-button>
                            </div>
                        </template>
                        <template>
                            <div class="text-center text-muted mb-4">
                                <small>Or sign up with credentials</small>
                            </div>
                            <form role="form">
                                <base-input alternative
                                            class="mb-3"
                                            placeholder="Name"
                                            addon-left-icon="ni ni-hat-3">
                                </base-input>
                                <base-input alternative
                                            class="mb-3"
                                            placeholder="Email"
                                            addon-left-icon="ni ni-email-83">
                                </base-input>
                                <base-input alternative
                                            type="password"
                                            placeholder="Password"
                                            addon-left-icon="ni ni-lock-circle-open">
                                </base-input>
                                <div class="text-muted font-italic">
                                    <small>password strength:
                                        <span class="text-success font-weight-700">strong</span>
                                    </small>
                                </div>
                                <base-checkbox>
                                    <span>I agree with the
                                        <a href="#">Privacy Policy</a>
                                    </span>
                                </base-checkbox>
                                <div class="text-center">
                                    <base-button type="primary" class="my-4">Create account</base-button>
                                </div>
                            </form>
                        </template>
                    </card>
                </div>
            </div>
        </div> -->
    </section>
</template>
<script>
export default {};
</script>
<style>
</style>
