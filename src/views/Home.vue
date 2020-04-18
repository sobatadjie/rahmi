<template>
  <div class="home">
      <HeaderRahmi />
      <HeroSection />      
      <WomenBanner />
      <InstaRahmi />
      <PartnerRahmi />
      <FooterRahmi />      
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderRahmi from '@/components/HeaderRahmi.vue'
import HeroSection from '@/components/HeroSection.vue'
import WomenBanner from '@/components/WomenBanner.vue'
import InstaRahmi from '@/components/InstaRahmi.vue'
import PartnerRahmi from '@/components/PartnerRahmi.vue'
import FooterRahmi from '@/components/FooterRahmi.vue'

export default {
  name: 'Home',
  components: {
    HeaderRahmi,
    HeroSection,
    WomenBanner,
    InstaRahmi,
    PartnerRahmi,
    FooterRahmi
  }
}
</script>
