<template>
  <body>
    <Preloader />

    <div id="main">
      <Header />

      <Slider />

      <Static />

      <BestSeller />

      <Categories />

      <!-- <HotDeals />

      <Banner />

      <Featured />

      -->
      <Banner2 /> 
      <!--
      <Recent />

      <Brand />
      -->
      <Footer/>
    </div>

    <Modal />
  </body>
</template>

<script>
import Preloader from "@/components/Preloader.vue";
import Header from "@/components/Header.vue";
import Slider from "@/components/Slider.vue";
import Static from "@/components/Static.vue";
import BestSeller from "@/components/BestSeller.vue";
import Categories from "@/components/Categories.vue";
import HotDeals from "@/components/HotDeals.vue";
import Banner from "@/components/Banner.vue";
import Featured from "@/components/Featured.vue";
import Banner2 from "@/components/Banner2.vue";
import Recent from "@/components/Recent.vue";
import Brand from "@/components/Brand.vue";
import Footer from "@/components/Footer.vue";
import Modal from "@/components/Modal.vue";

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
    Modal,
  },
  data() {
    return {};
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

</style>
