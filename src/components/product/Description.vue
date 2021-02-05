<template>
  <div class="description-review-area mb-60px">
    <div class="container">
      <div class="description-review-wrapper">
        <div class="description-review-topbar nav">
          <a data-toggle="tab" href="#des-details1">Description</a>
          <a class="active" data-toggle="tab" href="#des-details2"
            >Product Details</a
          >
          <a data-toggle="tab" href="#des-details3">Reviews </a>
        </div>
        <div class="tab-content description-review-bottom">
          <div id="des-details2" class="tab-pane active">
            <div class="product-anotherinfo-wrapper">
              <ul>
                <li><span>Weight</span> 1 Kg</li>
                <li><span>Dimensions</span>10 x 10 x 15 cm</li>
                <li><span>Type</span> Cousous</li>
              </ul>
            </div>
          </div>
          <div id="des-details1" class="tab-pane">
            <div class="product-description-wrapper">
              <p>
                Le couscous de blé entier est une excellente source de vitamines
                qui aident à augmenter les niveaux d’énergie corporelle et à
                améliorer les fonctions cérébrales. Il est également riche en
                glucides qui sont une excellente source d’énergie dont le corps
                a besoin pour les activités quotidiennes .lors de la cuisson du
                couscous, petit grain de pâte devient un peu plus grand et
                adoucissant, Ils sont généralement cuits avec des légumes et de
                la viande pour un plat plein et nutritif.
              </p>
            </div>
          </div>
          <div id="des-details3" class="tab-pane">
            <div class="row">
              <div class="col-lg-12">
                <div id="disqus_thread"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
//import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: "Blank",
  data() {
    return {};
  },
};
</script>
