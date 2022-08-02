<template>
  <div>
    <hero-section></hero-section>
    <snippet-section></snippet-section>
    <features-section></features-section>
    <access-anywhere></access-anywhere>
    <super-charge-section></super-charge-section>
    <refrences-section></refrences-section>
    <bottom-section></bottom-section>
    <footer-section></footer-section>
  </div>
</template>

<script>
import HeroSection from "../components/HeroSection.vue";
import SnippetSection from "../components/SnippetSection.vue";
import FeaturesSection from "../components/FeaturesSection.vue";
import AccessAnywhere from "../components/AccessAnywhere.vue";
import SuperChargeSection from "../components/SuperChargeSection.vue";
import RefrencesSection from "../components/RefrencesSection.vue";
import BottomSection from "../components/BottomSection.vue";
import FooterSection from "../components/FooterSection.vue";
export default {
  name: "App",
  components: {
    HeroSection,
    SnippetSection,
    FeaturesSection,
    AccessAnywhere,
    SuperChargeSection,
    RefrencesSection,
    BottomSection,
    FooterSection,
  },
};
</script>
