<script>
import HeroSection from "./HeroSection.vue"
import BusinessAreaSection from "./BusinessAreaSection.vue"
import AboutSection from "./AboutSection.vue"
import PortfolioSection from "./PortfolioSection.vue"
import ContactSection from "./ContactSection.vue"
import ResultsSection from "./ResultsSection.vue"

export default {
  components: {
    HeroSection,
    BusinessAreaSection,
    AboutSection,
    PortfolioSection,
    ContactSection,
    ResultsSection,
  },
  data() {
    return {
      
    };
  },
};
</script>

<template>
  <main>
    <HeroSection></HeroSection>

    <!-- Cards section business areas -->
    <BusinessAreaSection></BusinessAreaSection>

    <!-- About section The Company -->
    <AboutSection></AboutSection>
    
    <!-- Cards section Portfolio actions & Projects -->
    <PortfolioSection></PortfolioSection>

    <!-- Results  & Sponsors Section -->
    <ResultsSection></ResultsSection>

    <!-- Contact Section -->
    <ContactSection></ContactSection>

  </main>
</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;


</style>