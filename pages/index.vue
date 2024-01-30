<template>
    <div>
        <Navbar />
        <HomeMainBanner />
        <OurServices />
        <Statistics />
        <FunFact />
        <OurProducts />
        <DeliveryChannels />
        <OurMediaAssets />
        <OurDataStrategy />
        <CertificateAwards />
        <InsightsCTA />
        <OfficeLocation />
        <Footer />
    </div>
</template>

<script>
import Navbar from '../layouts/Navbar'
import HomeMainBanner from '../components/Index/HomeMainBanner'
import Statistics from '../components/Index/Statistics'
import OurServices from '../components/Index/OurServices'
import FunFact from '../components/Index/FunFact'
import OurProducts from '../components/Index/OurProducts'
import DeliveryChannels from '../components/Index/DeliveryChannels'
import OurMediaAssets from '../components/Index/OurMediaAssets'
import OurDataStrategy from '../components/Index/OurDataStrategy'
import CertificateAwards from '../components/Index/CertificateAwards'
import OfficeLocation from '../components/Index/OfficeLocation'
import InsightsCTA from '../components/Index/InsightsCTA'
import Footer from '../layouts/Footer'
import axios from 'axios';

export default {
    components: {
        Navbar,
        HomeMainBanner,
        OurServices,
        Statistics,
        FunFact,
        OurProducts,
        DeliveryChannels,
        OurMediaAssets,
        OurDataStrategy,
        CertificateAwards,
        InsightsCTA,
        OfficeLocation,
        Footer,
    },
    // data() {
    //     return {
    //         seoData: null,
    //     }
    // },
    // created: async function () {
    //     const { slug } = this.$route.params
    //     const reaponse = await axios.get(`https://evolvestrapi.pbwebvision.in/api/pages?filters[slug][$eq]=index&populate=deep,5`, { params: { slug } })
    //     this.details = reaponse.data.data;
    //     const pageData = this.details.length > 0 ? this.details[0] : {};
    //     if (pageData?.attributes?.seo) {
    //         this.seoData = pageData.attributes.seo;
    //     }
    // },
    // head({ $seo }) {
    //     return $seo({
    //         title: this.seoData?.metaTitle,
    //         description: this.seoData?.metaDescription,
    //         keywords: this.seoData?.keywords,
    //     });
    // },
}
</script>