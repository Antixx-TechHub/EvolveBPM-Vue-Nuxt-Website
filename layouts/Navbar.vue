<template>
    <div :class="['navbar-area', { 'is-sticky': isSticky }]">
        <div class="nav-bg-w main-header navfix fixed-top menu-white">
            <div class="container m-pad">
                <nav class="menu-header">
                    <NuxtLink class="dsk-logo nav-brand" to="/">
                        <img src="~/assets/images/logo.png" class="black-logo" alt="logo">
                        <!-- <img src="~/assets/images/white-logo.png" alt="logo"> -->
                    </NuxtLink>

                    <div>
                        <div class="menu2" @click="toggleMenu" :class="{ active: isMenuActive }">
                            <div class='top'></div>
                            <div class='middle'></div>
                            <div class='bottom'></div>

                        </div>
                        <div class="menu-box" :class="{ show: isMenuActive, active: isMenuActive }">
                            <NuxtLink class="navbar-brand" to="/">
                                <img src="~/assets/images/logo.png" alt="logo">
                            </NuxtLink>
                            <div class="menu2-items">
                                <div class="itemss">
                                    <NuxtLink to="/"> 
                                        <span style="color:#030303">Home</span>
                                    </NuxtLink>
                                </div>
                                <div class="itemss">
                                    <NuxtLink to="/"> 
                                        <span style="color:#030303">About Us</span>
                                    </NuxtLink>
                                </div>

                                <details class="accordion">
                                    <summary class="accordion-header">
                                        <div class="accordion-header-content">
                                            <!-- <h2 class="accordion-header-content-title">Title ipsum dolor</h2> -->
                                            <div class="itemss">
                                                Services
                                            </div>
                                        </div>
                                    </summary>
                                    <div class="accordion-content">
                                        <li>
                                            <nuxt-link to="/irev">
                                                <span> <img src="../assets/img/header-icon/keyword.png" alt=""> </span>
                                                 <span style="color:#030303">iRev</span>
                                            </nuxt-link>
                                        </li>
                                        <li>
                                            <nuxt-link to="/iintel">
                                                <span> <img src="../assets/img/header-icon/audit.png" alt=""> </span>
                                                <span style="color:#030303">iIntel</span>

                                                
                                            </nuxt-link>
                                        </li>
                                        <li>
                                            <nuxt-link to="/imedia">
                                                <span> <img src="../assets/img/header-icon/building.png" alt=""> </span>
                                                <span style="color:#030303">iMedia</span>
                                            </nuxt-link>
                                        </li>
                                        <li>
                                            <nuxt-link to="/innovator">
                                                <span> <img src="../assets/img/header-icon/media.png" alt=""> </span>
                                                <span style="color:#030303">Innovator</span>
                                            </nuxt-link>
                                        </li>
                                        <li>
                                            <nuxt-link to="/techbase">
                                                <span> <img src="../assets/img/header-icon/analysis.png" alt=""> </span>
                                                <span style="color:#030303">TechBase</span>
                                            </nuxt-link>
                                        </li>
                                    </div>
                                </details>

                                <details class="accordion">
                                    <summary class="accordion-header">
                                        <div class="accordion-header-content">
                                            <!-- <h2 class="accordion-header-content-title">Title ipsum dolor</h2> -->
                                            <div class="itemss">
                                                Products
                                            </div>
                                        </div>
                                    </summary>
                                    <div class="accordion-content">
                                        <li>
                                            <NuxtLink to="/irev">
                                                <span style="color:#030303">iRev</span>
                                            </NuxtLink>
                                        </li>
                                        <li>
                                            <NuxtLink to="/idata">
                                                <span style="color:#030303">iData</span>
                                            </NuxtLink>
                                        </li>
                                        <li>
                                            <NuxtLink to="/imedia">
                                                <span style="color:#030303">iMedia</span>
                                            </NuxtLink>
                                        </li>
                                    </div>
                                </details>

                                <details class="accordion">
                                    <summary class="accordion-header">
                                        <div class="accordion-header-content">
                                            <!-- <h2 class="accordion-header-content-title">Title ipsum dolor</h2> -->
                                            <div class="itemss">
                                                Company
                                            </div>
                                        </div>
                                    </summary>
                                    <div class="accordion-content">
                                        <li>
                                            <NuxtLink to="/careers">
                                                <span style="color:#030303">careers</span>
                                            </NuxtLink>
                                        </li>
                                        <li>
                                            <NuxtLink to="/our-team">
                                                
                                                <span style="color:#030303">Our Team</span>
                                            </NuxtLink>
                                        </li>
                                        <li>
                                            <NuxtLink to="/team-details">                                               
                                               <span style="color:#030303">Team Details</span>
                                            </NuxtLink>
                                        </li>
                                        <li>
                                            <NuxtLink to="/faqs">                                               
                                                <span style="color:#030303">FAQ's</span>
                                            </NuxtLink>
                                        </li>
                                    </div>
                                </details>

                                <details class="accordion">
                                    <summary class="accordion-header">
                                        <div class="accordion-header-content">
                                            <!-- <h2 class="accordion-header-content-title">Title ipsum dolor</h2> -->
                                            <div class="itemss">
                                                Resources
                                            </div>
                                        </div>
                                    </summary>
                                    <div class="accordion-content">
                                        <li>
                                            <NuxtLink to="/blogs">
                                                <span style="color:#030303">Blogs</span>
                                            </NuxtLink>
                                        </li>
                                        <li>
                                            <NuxtLink to="/success-stories">
                                                <span style="color:#030303">Success Stories</span>
                                            </NuxtLink>
                                        </li>
                                        <li>
                                            <NuxtLink to="/case-studies">
                                                <span style="color:#030303">Case Studies</span>
                                            </NuxtLink>
                                        </li>
                                    </div>
                                </details>

                                <div class="itemss">
                                    <NuxtLink to="/"> 
                                        <span style="color:#030303">Contact Us</span>
                                    </NuxtLink>
                                </div>
                            </div>

                            <!-- <div class="banner-btn solution-video pb-70">
                                <NuxtLink to="/contact" class="default-btn-one">
                                    Get A Free Trail <i class="fas fa-chevron-right"></i>
                                </NuxtLink>
                            </div> -->

                            <div class="-cta-btn mt-5">
                                <div class="free-cta-title v-center wow zoomInDown" data-wow-delay="1.1s">
                                    <a href="#" class="btn-main bg-btn lnk">Get A Free Trail <i
                                            class="fas fa-chevron-right fa-icon"></i><span class="circle"></span></a>
                                </div>
                            </div>
                            <ul class="list-unstyled -address-list-one pb-70 ">
                                <h4>
                                    <li> <a href="tel:+91-020-69029999"><i class="fas fa-phone-alt"></i>
                                            +91-020-69029999</a></li>
                                </h4>
                                <li><a href="mailto:corporate@evolvebpm.com"><i class="fas fa-envelope"></i>
                                        corporate@evolvebpm.com</a></li>
                            </ul>


                            <div class="ff-social-icons">
                                <a href="https://www.facebook.com/EvolveBPM/" target="blank">
                                    <img src="~/assets/images/fb.png" alt="logo">
                                </a>
                                <a href="https://www.twitter.com/evolvebpm" target="blank">
                                    <img src="~/assets/images/twitters.png" alt="logo">
                                </a>
                                <a href="https://www.instagram.com/evolvebpm/" target="blank">
                                    <img src="~/assets/images/insta.png" alt="logo">
                                </a>
                                <a href="https://www.linkedin.com/company/evolve-bpm/" target="blank">
                                    <img src="~/assets/images/linkedin.png" alt="logo">
                                </a>
                                <a href="javascript:void(0)" target="blank">
                                    <img src="~/assets/images/youtube.png" alt="logo">
                                </a>
                            </div>
                        </div>
                    </div>
                </nav>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Navbar',
    components: {

    },
    data() {
        return {
            isSticky: false,
            isSearch: false,
            items: [
                { isActive: false },
                { isActive: false },
            ],
            isMenuActive: false,
        }
    },

    mounted() {
        const that = this
        window.addEventListener('scroll', () => {
            let scrollPos = window.scrollY
            if (scrollPos >= 100) {
                that.isSticky = true
            } else {
                that.isSticky = false
            }
        })
    },

    methods: {
        toggleMenu() {
            this.isMenuActive = !this.isMenuActive;
        },
        toggleDropdown() {
            this.isDropdownOpen = !this.isDropdownOpen;
        },
        handleDropdownItemClick() {
            // Logic to handle dropdown item click
            console.log('Dropdown item clicked!');
            // You can add further logic here
        },
        toggleCollapse(index) {
            this.$set(this.items, index, {
                isActive: !this.items[index].isActive,
            });
        },
    }
}
</script>