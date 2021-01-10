<template>
  <section class="best-sells-area mb-30px">
    <div class="container">
      <!-- Section Title Start -->
      <div class="row">
        <div class="col-md-12">
          <div class="section-title">
            <h2>Les meilleures ventes</h2>
          </div>
        </div>
      </div>
      <!-- Section Title End -->

      <div class="best-sell-slider owl-carousel owl-nav-style">
        
        <article v-for="article in BestSellers" :key="article" class="list-product">
          <div class="img-block">
            <a :href="article.link" class="thumbnail">
              <img
                class="first-img"
                :src="article.img1"
                alt=""
              />
              <img
                class="second-img"
                :src="article.img2"
                alt=""
              />
            </a>
            <div class="quick-view">
              <a
                class="quick_view"
                :href="article.link"
                data-link-action="quickview"
                title="Quick view"
                data-toggle="modal"
                data-target="#exampleModal"
              >
                <i class="ion-ios-search-strong"></i>
              </a>
            </div>
          </div>
          <ul class="product-flag">
            <li class="new">New</li>
          </ul>
          <div class="product-decs">
            <a class="inner-link" :href="article.link"
              ><span> {{article.bio}} </span></a
            >
            <h2>
              <a :href="article.link" class="product-link"
                > {{article.title}} </a
              >
            </h2>
            <div class="rating-product">
              <i v-for="el in article.stars" :key="el" class="ion-android-star"></i>
            </div>
            <div class="pricing-meta">
              <ul>
                <li class="old-price"> {{article.oldPrice}} MAD </li>
                <li class="current-price"> {{article.currentPrice}} MAD </li>
                <li class="discount-price">-{{article.discount}}%</li>
              </ul>
            </div>
          </div>
          <div class="add-to-link">
            <ul>
              <li class="cart">
                <a class="cart-btn" :href="article.link">ACHETER </a>
              </li>
              
            </ul>
          </div>
        </article>
       
      </div>
      
    </div>
  </section>
</template>

<script>
export default {
  name: "BestSeller",
  data() {
    return {
      BestSellers:[
        {
        link: '#',
        img1: 'assets/images/product-image/organic/product-15.jpg',
        img2: 'assets/images/product-image/organic/product-2.jpg',
        bio: 'BIO',
        title: 'Juicy Couture Juicy Quilted Ter..',
        stars: 5,
        oldPrice: 35,
        currentPrice: 34,
        discount: 5
      },
      {
        link: '#',
        img1: 'assets/images/product-image/organic/product-15.jpg',
        img2: 'assets/images/product-image/organic/product-2.jpg',
        bio: 'BIO',
        title: 'Juicy Couture Juicy Quilted Ter..',
        stars: 5,
        oldPrice: 35,
        currentPrice: 34,
        discount: 5
      },{
        link: '#',
        img1: 'assets/images/product-image/organic/product-15.jpg',
        img2: 'assets/images/product-image/organic/product-2.jpg',
        bio: 'BIO',
        title: 'Juicy Couture Juicy Quilted Ter..',
        stars: 5,
        oldPrice: 35,
        currentPrice: 34,
        discount: 5
      },{
        link: '#',
        img1: 'assets/images/product-image/organic/product-15.jpg',
        img2: 'assets/images/product-image/organic/product-2.jpg',
        bio: 'BIO',
        title: 'Juicy Couture Juicy Quilted Ter..',
        stars: 5,
        oldPrice: 35,
        currentPrice: 34,
        discount: 5
      },{
        link: '#',
        img1: 'assets/images/product-image/organic/product-15.jpg',
        img2: 'assets/images/product-image/organic/product-2.jpg',
        bio: 'BIO',
        title: 'Juicy Couture Juicy Quilted Ter..',
        stars: 5,
        oldPrice: 35,
        currentPrice: 34,
        discount: 5
      },{
        link: '#',
        img1: 'assets/images/product-image/organic/product-15.jpg',
        img2: 'assets/images/product-image/organic/product-2.jpg',
        bio: 'BIO',
        title: 'Juicy Couture Juicy Quilted Ter..',
        stars: 5,
        oldPrice: 35,
        currentPrice: 34,
        discount: 5
      },{
        link: '#',
        img1: 'assets/images/product-image/organic/product-15.jpg',
        img2: 'assets/images/product-image/organic/product-2.jpg',
        bio: 'BIO',
        title: 'Juicy Couture Juicy Quilted Ter..',
        stars: 5,
        oldPrice: 35,
        currentPrice: 34,
        discount: 5
      },{
        link: '#',
        img1: 'assets/images/product-image/organic/product-15.jpg',
        img2: 'assets/images/product-image/organic/product-2.jpg',
        bio: 'BIO',
        title: 'Juicy Couture Juicy Quilted Ter..',
        stars: 5,
        oldPrice: 35,
        currentPrice: 34,
        discount: 5
      },{
        link: '#',
        img1: 'assets/images/product-image/organic/product-15.jpg',
        img2: 'assets/images/product-image/organic/product-2.jpg',
        bio: 'BIO',
        title: 'Juicy Couture Juicy Quilted Ter..',
        stars: 5,
        oldPrice: 35,
        currentPrice: 34,
        discount: 5
      },{
        link: '#',
        img1: 'assets/images/product-image/organic/product-15.jpg',
        img2: 'assets/images/product-image/organic/product-2.jpg',
        bio: 'BIO',
        title: 'Juicy Couture Juicy Quilted Ter..',
        stars: 5,
        oldPrice: 35,
        currentPrice: 34,
        discount: 5
      },
      ],
      
    };
  },
};
</script>
