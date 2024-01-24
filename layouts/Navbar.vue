<template>
    <div :class="['navbar-area', { 'is-sticky': isSticky }]">
        <div class="nav-bg-w main-header navfix fixed-top menu-white">
            <div class="container m-pad">
                <nav class="menu-header">
                    <NuxtLink class="dsk-logo nav-brand" to="/">
                        <img src="~/assets/images/logo.png" alt="logo">
                    </NuxtLink>

                    <b-navbar-toggle class="btn-round- btn-br bg-btn3" data-bs-toggle="offcanvas"
                        target="navbarSupportedContent">
                        <i class="fas fa-qrcode"></i>
                    </b-navbar-toggle>

                    <b-collapse class="custom-nav" role="navigation" id="navbarSupportedContent" is-nav>
                        <ul class="nav-list onepge">
                            <li class="menu-links">
                                <NuxtLink to="/" class="nav-link">
                                    Home
                                </NuxtLink>
                            </li>

                            <li class="menu-links">
                                <NuxtLink to="/about-us" class="nav-link">
                                    About Us
                                </NuxtLink>
                            </li>

                            <li class="menu-links">
                                <NuxtLink to="/about-one" class="nav-link">
                                    Services <i class="fas fa-chevron-down"></i>
                                </NuxtLink>
                                <ul class="sub-menu-column">
                                    <li>
                                        <nuxt-link to="/irev" class="nav-link">
                                            <span> <img src="../assets/img/header-icon/keyword.png" alt=""> </span>
                                            iRev
                                        </nuxt-link>
                                    </li>
                                    <li>
                                        <nuxt-link to="/iintel" class="nav-link">
                                            <span> <img src="../assets/img/header-icon/audit.png" alt=""> </span>
                                            iIntel
                                        </nuxt-link>
                                    </li>
                                    <li>
                                        <nuxt-link to="/imedia" class="nav-link">
                                            <span> <img src="../assets/img/header-icon/building.png" alt=""> </span>
                                            iMedia
                                        </nuxt-link>
                                    </li>
                                    <li>
                                        <nuxt-link to="/innovator" class="nav-link">
                                            <span> <img src="../assets/img/header-icon/media.png" alt=""> </span>
                                            Innovator
                                        </nuxt-link>
                                    </li>
                                    <li>
                                        <nuxt-link to="/techbase" class="nav-link">
                                            <span> <img src="../assets/img/header-icon/analysis.png" alt=""> </span>
                                            TechBase
                                        </nuxt-link>
                                    </li>
                                </ul>
                            </li>

                            <li class="menu-links">
                                <NuxtLink to="/#" class="nav-link">
                                    Our Products <i class="fas fa-chevron-down"></i>
                                </NuxtLink>
                                <ul class="dropdown-menu">
                                    <li class="nav-item">
                                        <NuxtLink to="/irev" class="nav-link">iRev</NuxtLink>
                                    </li>
                                    <li class="nav-item">
                                        <NuxtLink to="/idata" class="nav-link">iData</NuxtLink>
                                    </li>
                                    <li class="nav-item">
                                        <NuxtLink to="/imedia" class="nav-link">iMedia</NuxtLink>
                                    </li>
                                </ul>
                            </li>

                            <li class="menu-links">
                                <NuxtLink to="/#" class="nav-link">
                                    Company <i class="fas fa-chevron-down"></i>
                                </NuxtLink>
                                <ul class="dropdown-menu">
                                    <li class="nav-item">
                                        <NuxtLink to="/careers" class="nav-link">Careers</NuxtLink>
                                    </li>
                                    <li class="nav-item">
                                        <NuxtLink to="/our-team" class="nav-link">Our Team</NuxtLink>
                                    </li>
                                </ul>
                            </li>

                            <li class="menu-links">
                                <a href="/resources" class="nav-link">
                                    Resources<i class="fas fa-chevron-down"></i>
                                </a>
                                <ul class="dropdown-menu">
                                    <li class="nav-item">
                                        <NuxtLink to="/blogs" class="nav-link">Blogs</NuxtLink>
                                    </li>
                                    <li class="nav-item">
                                        <NuxtLink to="/sucess-stories" class="nav-link">Sucess Stories</NuxtLink>
                                    </li>
                                    <li class="nav-item">
                                        <NuxtLink to="/case-studies" class="nav-link">Case Studies</NuxtLink>
                                    </li>

                                </ul>
                            </li>

                            <li class="menu-links">
                                <NuxtLink to="/contact-us" class="nav-link">Contact</NuxtLink>
                            </li>

                            <div class="mobile-menu2">
                                <ul class="mob-nav2">
                                    <li><a class="btn-round- trngl btn-br bg-btn btshad-b1" data-bs-toggle="offcanvas"
                                            href="#offcanvasExample"><i class="fas fa-qrcode"></i></a></li>
                                    <li class="navm-"> <a class="toggle" href="#"><span></span></a></li>
                                </ul>
                            </div>
                        </ul>
                    </b-collapse>
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
            isSearch: false
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
}
</script>