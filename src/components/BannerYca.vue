
<template>
  <!-- Women Banner Section Begin -->
  <section class="women-banner spad">
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-12 mt-5">
          <carousel class="product-slider" :items="3" :dots="false" :autoplay="true" :nav="false">
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/Kontak.png" alt />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Rekomendasi</div>
                <router-link to="/product">
                  <a href="#">
                    <h5>Kelas Presentasi</h5>
                  </a>
                </router-link>
                <div class="product-price">
                  Rp.149.000
                  <span>Rp.700.000</span>
                </div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/KelasReguler.jpeg" alt />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <a href="#">+ Quick View</a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Paket Hemat</div>
                <a href="#">
                  <h5>Kelas Public Speaking</h5>
                </a>
                <div class="product-price">
                  Rp.299.000
                  <span>Rp.1.500.000</span>
                </div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/onlineClass.jpg" alt />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <a href="#">+ Quick View</a>
                  </li>
                  <li class="w-icon">
                    <a href="#">
                      <i class="fa fa-random"></i>
                    </a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Paling Laris</div>
                <a href="#">
                  <h5>Kelas Online</h5>
                </a>
                <div class="product-price">
                  Rp.49.000
                  <span>Rp.1.000.000</span>
                </div>
              </div>
            </div>
          </carousel>
        </div>
      </div>
    </div>
  </section>
  <!-- Yca Banner Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "BannerYca",
  components: {
    carousel
  }
};
</script>

<style scoped>
.product-item {
  margin-right: 25px;
}
.pi-pic img {
  height: 450px;
}
</style>

