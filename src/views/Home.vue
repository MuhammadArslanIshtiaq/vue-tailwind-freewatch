<template>
  <main class="home">
    <HeroSection />
    <AvailableSection />
  </main>
</template>

<script>
import AvailableSection from "../components/Home/AvailableSection.vue";
// @ is an alias to /src
import HeroSection from "../components/Home/HeroSection.vue";

export default {
  name: "Home",
  components: {
    HeroSection,
    AvailableSection,
  },
};
</script>
