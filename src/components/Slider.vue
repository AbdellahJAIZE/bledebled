<template>
  <div class="slider-area">
    <div class="slider-active-3 owl-carousel slider-hm8 owl-dot-style">
      <!-- Slider Single Item Start -->
      <div
        class="slider-height-6 d-flex align-items-start justify-content-start bg-img"
        style="background-image: url(/assets/images/slider-image/couscous.jpg);"
      >
        <div class="container">
          <div class="slider-content-1 slider-animated-1 text-left">
            <span class="animated">{{item1.text1}}</span>
            <h1 class="animated">
             {{item1.text2}}  <br />
              {{item1.text3}}
            </h1>
            <p class="animated">
              {{item1.text4}}
            </p>
            <a href="#" class="shop-btn animated">SHOP NOW</a>
          </div>
        </div>
      </div>
      <!-- Slider Single Item End -->
      <!-- Slider Single Item Start -->
      <div
        class="slider-height-6 d-flex align-items-start justify-content-start bg-img"
        style="background-image: url(assets/images/slider-image/farine.jpg);"
      >
        <div class="container">
          <div class="slider-content-1 slider-animated-1 text-left">
            <span class="animated">{{item2.text1}}</span>
            <h1 class="animated">
              {{item2.text2}} <br />
              {{item2.text3}}
            </h1>
            <p class="animated">{{item2.text4}}</p>
            <a href="#" class="shop-btn animated">SHOP NOW</a>
          </div>
        </div>
      </div>
      <!-- Slider Single Item End -->
    </div>
  </div>
</template>

<script>
export default {
  name: "Slider",
  data() {
    return {
      item1:{
        text1: "Couscous Complet",
        text2: 'Bien Monger,',
        text3: 'Pour mieux vivre',
        text4: 'Ultra Rapide',
      },
      item2:{
        text1: "Farine d'orge",
        text2: 'Bien Monger,',
        text3: 'Pour mieux vivre',
        text4: 'Ultra Rapide',
      }
    };
  },
};
</script>
