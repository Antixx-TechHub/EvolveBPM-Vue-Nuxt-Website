<template>
    <div class="footerdez footerdex dark-footer pt50">
      <div class="container">
        <div class="row justify-content-between">
          <div class="col-lg-12 col-sm-12">
            <div class="row fttlnks">
              <div class="col-lg-4 col-sm-12">
                <div class="footerdez-a">
                  <NuxtLink class="navbar-brand mt30 f-dark-logo" to="/">
                    <img src="~/assets/images/white-logo.png" alt="Logo" />
                  </NuxtLink>
                  <p class="mt10">
                    Lorem ipsum dolor sit amet, is consectetur adipiscing elit,
                    sed do ipsum lorem dollar eiusmo. Lorem ipsum dolor sit amet,
                    is sit consectetur adipiscing elit.
                  </p>
                </div>
                <h5 class="mt20">Follow Us</h5>
                <div class="ff-social-icons">
                  <a href="javascript:void(0)" target="blank"
                    ><i class="fab fa-facebook"></i
                  ></a>
                  <a href="javascript:void(0)" target="blank"
                    ><i class="fab fa-twitter"></i
                  ></a>
                  <a href="javascript:void(0)" target="blank"
                    ><i class="fab fa-instagram"></i
                  ></a>
                  <a href="javascript:void(0)" target="blank"
                    ><i class="fab fa-linkedin"></i
                  ></a>
                  <a href="javascript:void(0)" target="blank"
                    ><i class="fab fa-youtube"></i
                  ></a>
                </div>
              </div>
              <div class="col-lg-2 col-sm-6 pt40">
                <h5>COMPANY</h5>
                <ul class="footer-address-list link-hover">
                  <li><NuxtLink to="/about">About Us</NuxtLink></li>
                  <li><NuxtLink to="/leadership">Leadership</NuxtLink></li>
                  <li>
                    <NuxtLink to="/methodology">Our Methodology (DDIA)</NuxtLink>
                  </li>
                  <li><NuxtLink to="/careers">Careers</NuxtLink></li>
                  <li><NuxtLink to="/csr">CSR Activities</NuxtLink></li>
                  <li><NuxtLink to="/contact">Contact us</NuxtLink></li>
                  <li><NuxtLink to="/request-demo">Request Demo</NuxtLink></li>
                </ul>
              </div>
              <div class="col-lg-2 col-sm-6 pt40">
                <h5>SERVICES</h5>
                <ul class="footer-address-list link-hover">
                  <li><NuxtLink to="/services/irev">iRev</NuxtLink></li>
                  <li><NuxtLink to="/services/idata">iData</NuxtLink></li>
                  <li><NuxtLink to="/services/imedia">iMedia</NuxtLink></li>
                </ul>
              </div>
              <div class="col-lg-2 col-sm-6 pt40">
                <h5>PRODUCTS</h5>
                <ul class="footer-address-list link-hover">
                  <li><NuxtLink to="/products/innovator">Innovator</NuxtLink></li>
                  <li><NuxtLink to="/products/predictor">Predictor</NuxtLink></li>
                  <li><NuxtLink to="/products/intello">Intello</NuxtLink></li>
                </ul>
              </div>
              <div class="col-lg-2 col-sm-6 pt40">
                <h5>INSIGHTS</h5>
                <ul class="footer-address-list link-hover">
                  <li><NuxtLink to="/blogs">Blogs</NuxtLink></li>
                  <li><NuxtLink to="/pillar-pages">Pillar pages</NuxtLink></li>
                  <li><NuxtLink to="/whitepapers">Whitepapers</NuxtLink></li>
                  <li><NuxtLink to="/ebooks">Ebooks</NuxtLink></li>
                  <li><NuxtLink to="/case-studies">Case studies</NuxtLink></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
  
      <div class="dark-footer dg-bg--2 nshape">
        <div class="container">
          <div class="row end-footer-">
            <div class="col-lg-6">
              <div class="footer-copyrights-">
                <p>
                  &copy; 2024 All rights reserved.
                  <a href="https://www.evolvebpm.com/" target="_blank"
                    >Evolve BPM</a
                  >
                </p>
              </div>
            </div>
            <div class="col-lg-6">
              <ul class="footer-link-- link-hover">
                <li><NuxtLink to="/privacy-policy">Privacy</NuxtLink></li>
                <li><NuxtLink to="/gdpr">GDPR</NuxtLink></li>
                <li><NuxtLink to="/casl">CASL</NuxtLink></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Footer',
  };
  </script>
  