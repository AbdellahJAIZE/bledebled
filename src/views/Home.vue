<template>
  <body>
    <!--====== PRELOADER PART START ======-->
    <Preloader/> 
    <!--====== PRELOADER PART ENDS ======-->

    <div id="main">

      <!-- Header Start -->
      <Header/>
      <!-- Header End -->

      <!-- Slider Arae Start -->
      <Slider/>
      <!-- Slider Arae End -->

      <!-- Static Area Start -->
      <Static/>
      <!-- Static Area End -->

      <!-- Best Sells Area Start -->
      <BestSeller/>
      <!-- Best Sells Slider End -->

      <!-- Category Area Start -->
      <Categories/>
      <!-- Category Area End  -->

      <!-- Hot deal area Start -->
      <HotDeals/>
      <!-- Hot Deal Area End -->

      <!-- Banner Area Start -->
      <Banner/>
      <!-- Banner Area End -->

      <!-- Feature Area Start -->
      <Featured/>
      <!-- Feature Area End -->

      <!-- Banner Area 2 Start -->
      <Banner2/>
      <!-- Banner Area 2 End -->

      <!-- Recent Add Product Area Start -->
      <Recent/>
      <!-- Recent product area end -->

      <!-- Brand area start -->
      <Brand/>
      <!-- Brand area end -->

      <!-- Footer Area start -->
      <Footer></Footer>
      <!--  Footer Area End -->
    </div>

    <!-- Modal start -->
    <Modal/>
    <!-- Modal End -->
  </body>
</template>

<script>

import Preloader from '@/components/Preloader.vue'
import Header from '@/components/Header.vue'
import Slider from '@/components/Slider.vue'
import Static from '@/components/Static.vue'
import BestSeller from '@/components/BestSeller.vue'
import Categories from '@/components/Categories.vue'
import HotDeals from '@/components/HotDeals.vue'
import Banner from '@/components/Banner.vue'
import Featured from '@/components/Featured.vue'
import Banner2 from '@/components/Banner2.vue'
import Recent from '@/components/Recent.vue'
import Brand from '@/components/Brand.vue'
import Footer from '@/components/Footer.vue'
import Modal from '@/components/Modal.vue'


export default {
  name: "Home",
  components: {
    Preloader,
    Header,
    Slider,
    Static,
    BestSeller,
    Categories,
    HotDeals,
    Banner,
    Featured,
    Banner2,
    Recent,
    Brand,
    Footer,
    Modal
  },
  data() {
    return{
      
    }
  },
  created() {
    //load main script
    const script = document.createElement("script");
    script.src = "assets/js/main.js";
    document.head.appendChild(script);
  },
};
</script>

<style scoped>
  .bg-img1 {
    background-image: url(/assets/images/slider-image/sample-1.jpg);
  }
</style>
