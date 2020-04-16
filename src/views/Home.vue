<template>
  <div class="home">
    <HeaderYca />
    <HeroYca />
    <BannerYca />
    <InstaYca />
    <PartnerYca />
    <FooterYca />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderYca from "@/components/HeaderYca.vue";
import HeroYca from "@/components/HeroYca.vue";
import BannerYca from "@/components/BannerYca.vue";
import InstaYca from "@/components/InstaYca.vue";
import PartnerYca from "@/components/PartnerYca.vue";
import FooterYca from "@/components/FooterYca.vue";

export default {
  name: "home",
  components: {
    HeaderYca,
    HeroYca,
    BannerYca,
    InstaYca,
    PartnerYca,
    FooterYca
  }
};
</script>
