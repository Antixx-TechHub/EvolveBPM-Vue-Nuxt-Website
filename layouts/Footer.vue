<!-- components/Footer.vue -->
<template>
    <footer class="dark-footer dg-bg--1 pt60 nshape dark-footer-1">
        <div class="container">
            <div class="row justify-content-between">

                <!-- Previous code -->
                <div class="col-lg-4 col-sm-6 ftr-brand-pp">
                    <!-- ... (Previous code) ... -->
                </div>

                <div class="col-lg-3 col-sm-6">
                    <!-- ... (Previous code) ... -->
                </div>

                <div class="col-lg-2 col-sm-6">
                    <!-- ... (Previous code) ... -->
                </div>

                <div class="col-lg-3 col-sm-6 footer-blog-">
                    <!-- ... (Previous code) ... -->
                </div>

                <!-- New code -->
                <div class="col-lg-3 col-md-6 col-sm-6">
                    <div class="single-footer-card">
                        <NuxtLink to="/" class="logo">
                            <img src="~/assets/images/white-logo.png" alt="logo">
                        </NuxtLink>
                        <p>Lorem ipsum dolor sit amet, is consectetur adipiscing elit, sed do ipsum lorem dollar eiusmo.
                            Lorem ipsum dolor sit amet, is sit consectetur adipiscing elit.</p>
                        <ul class="social-links">
                            <!-- ... (New code) ... -->
                        </ul>
                    </div>
                </div>

                <div class="col-lg-3 col-md-6 col-sm-6">
                    <div class="footer-address-list link-hover">
                        <h5 class="mb30 mt30">Company</h5>
                        <ul class="footer-address-list link-hover">
                            <li>
                                <NuxtLink to="/about-us"><i class="fas fa-angle-double-right"></i> About Us</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/leadership"><i class="fas fa-angle-double-right"></i> Leadership</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/our-methodology"><i class="fas fa-angle-double-right"></i> Our Methodology
                                    (DDIA)</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/careers"><i class="fas fa-angle-double-right"></i> Careers</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/csr-activities"><i class="fas fa-angle-double-right"></i> CSR Activities
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/contact-us"><i class="fas fa-angle-double-right"></i> Contact us</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/request-demo"><i class="fas fa-angle-double-right"></i> Request Demo
                                </NuxtLink>
                            </li>
                        </ul>
                    </div>
                </div>

                <div class="col-lg-2 col-md-6 col-sm-6">
                    <div class="single-footer-card ps-5">
                        <h5 class="mb30 mt30">Services</h5>
                        <ul class="footer-address-list link-hover">
                            <li>
                                <NuxtLink to="/irev"><i class="fas fa-angle-double-right"></i> iRev</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/idata"><i class="fas fa-angle-double-right"></i> iData</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/imedia"><i class="fas fa-angle-double-right"></i> iMedia</NuxtLink>
                            </li>
                        </ul>
                    </div>
                </div>

                <div class="col-lg-2 col-md-6 col-sm-6">
                    <div class="single-footer-card ps-5">
                        <h5 class="mb30 mt30">Products</h5>
                        <ul class="footer-address-list link-hover">
                            <li>
                                <NuxtLink to="/innovator"><i class="fas fa-angle-double-right"></i> Innovator</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/predictor"><i class="fas fa-angle-double-right"></i> Predictor</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/intello"><i class="fas fa-angle-double-right"></i> Intello</NuxtLink>
                            </li>
                        </ul>
                    </div>
                </div>

                <div class="col-lg-2 col-md-6 col-sm-6">
                    <div class="single-footer-card ps-5">
                        <h5 class="mb30 mt30">Insights</h5>
                        <ul class="footer-address-list link-hover">
                            <li>
                                <NuxtLink to="/blogs"><i class="fas fa-angle-double-right"></i> Blogs</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/pillar-pages"><i class="fas fa-angle-double-right"></i> Pillar pages
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/whitepapers"><i class="fas fa-angle-double-right"></i> Whitepapers</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/ebooks"><i class="fas fa-angle-double-right"></i> Ebooks</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/case-studies"><i class="fas fa-angle-double-right"></i> Case studies
                                </NuxtLink>
                            </li>
                        </ul>
                    </div>
                </div>

            </div>

            <div class="row end-footer-">
                <div class="col-lg-6">
                    <div class="footer-copyrights-">
                        <p>&copy; {{ currentYear }}. All rights reserved. <a href="https://www.evolvebpm.com/"
                                target="_blank">Evolve BPM</a></p>
                    </div>
                </div>
                <div class="col-lg-6">
                    <ul class="footer-link-- link-hover">
                        <li>
                            <NuxtLink to="/privacy-policy">Privacy</NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/gdpr">GDPR</NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/casl">CASL</NuxtLink>
                        </li>
                    </ul>
                </div>
            </div>

        </div>
    </footer>
</template>
  
<script>
export default {
    // Component logic goes here
}
</script>
  
<style scoped>/* Component-specific styles go here */</style>