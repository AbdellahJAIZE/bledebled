<template>
  <div class="header-top-nav">
    <div class="container-fluid">
      <div class="row">
        <!--Left Start-->
        <div class="col-lg-4 col-md-4">
          <div class="left-text">
            <p>{{welcome}}</p>
          </div>
        </div>
        <!--Left End-->
        <!--Right Start-->
        <div class="col-lg-8 col-md-8 text-right">
          <div class="header-right-nav">
            
            <div class="dropdown-navs">
              <ul>
                <!-- Currency Start -->
                <li class="top-10px first-child">
                  <select>
                    <option value="1">MAD</option>
                  </select>
                </li>
                <!-- Currency End -->
                <!-- Language Start -->
                <li class="top-10px mr-15px">
                  <select>
                    <option value="1">Francais</option>
                  </select>
                </li>
                <!-- Language End -->
              </ul>
            </div>
          </div>
        </div>
        <!--Right End-->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Ribon",
  data() {
    return {
      welcome : 'Bienvenue dans le magasin de Bledebled !'
    };
  },
};
</script>
