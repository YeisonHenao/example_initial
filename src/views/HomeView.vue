<template>
  <BannerVue/>
  <SectionVue />
  <FooterVue />
</template>

<script>
import BannerVue from '@/components/Banner.vue';
import FooterVue from '@/components/Footer.vue';
import SectionVue from '@/components/Section.vue';

export default {
  name: "HomeView",
  components:{
    BannerVue,
    FooterVue,
    SectionVue
  }
};
</script>
