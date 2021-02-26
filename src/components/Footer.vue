<template>
  <footer class="footer-area">
    <div class="footer-top" style="padding: 30px 0;">
      <div class="container">
        <div class="row">
          <!-- footer single wedget -->
          <div class="col-md-6 col-lg-4">
            <!-- footer logo -->
            <div class="footer-logo">
              <a href="index.html"
                ><img src="assets/images/logo/logo1.jpg" alt=""
              /></a>
            </div>
            <!-- footer logo -->
            <div class="about-footer">
              <br />
              <div class="need-help">
                <p class="phone-info">
                  BESOIN D'AIDE ?
                  <span>
                    {{ phone }}
                  </span>
                </p>
              </div>
              <div class="social-info">
                <ul>
                  <li>
                    <a href="#"><i class="ion-social-facebook"></i></a>
                  </li>

                  <li>
                    <a href="#"><i class="ion-social-instagram"></i></a>
                  </li>
                </ul>
              </div>
              <br>
              <div>
                <p class="copy-text">
                  Copyright © <a href="https://fva.ma/"> FVA</a>. Tous droits réservés
                </p>
              </div>
            </div>
          </div>
          <!-- footer single wedget -->
          <div class="col-md-6 col-lg-8">
            <div class="single-wedge">
              <img
                src="/assets/images/logo.png"
                style="display: block; margin-left: auto; margin-right: auto; width: 50%;"
                height="273"
                width="385"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      phone: "(+212) 6 00000000",
    };
  },
};
</script>
