<template>
  <header class="main-header">
    <Ribon />

    <div class="header-navigation sticky-nav">
      <div class="container-fluid">
        <div class="row">
          <!-- Logo Start -->
          <div class="col-md-2 col-sm-2">
            <div class="logo">
              <a href="/"
                ><img src="/assets/images/logo/logo1.jpg" alt="logo.jpg"
              /></a>
            </div>
          </div>
          <!-- Logo End -->
          <!-- Navigation Start -->
          <div class="col-md-10 col-sm-10">
            <!--Main Navigation Start -->
            <div class="main-navigation d-none d-lg-block">
              <ul>
                <li class="menu-dropdown" v-for="link in links" :key="link">
                  <a :href="link.Path">{{link.Name}}</a>
                </li>
                
              </ul>
            </div>
            <!--Main Navigation End -->
            <!--Header Bottom Account Start -->
            <div class="header_account_area">
              
              <!--Contact info Start -->
              <div class="contact-link">
                <div class="phone">
                  <p>Appelez Nous :</p>
                  <a :href="'tel:'+phone">{{phone}}</a>
                </div>
              </div>
              <!--Contact info End -->
              
            </div>
          </div>
        </div>
        <!-- mobile menu -->
        <div class="mobile-menu-area">
          <div class="mobile-menu">
            <nav id="mobile-menu-active">
              <ul class="menu-overflow">
                <li v-for="link in links" :key="link">
                  <a :href="link.Path">{{link.Name}}</a>
                </li>
                
              </ul>
            </nav>
          </div>
        </div>
        <!-- mobile menu end-->
      </div>
    </div>
  </header>
</template>

<script>
import Ribon from "@/components/Ribon.vue";

export default {
  components: { Ribon },
  name: "Header",
  data() {
    return {
      phone: '(+212) 6 61566046',
      links:[
        { Name:'Accueil', Path:'/'},
        { Name:'Boutique', Path:'/shop'},
        { Name:'Contactez-nous', Path:'/contact'},
      ]
    };
  },
};
</script>

