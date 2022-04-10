<template>
  <main class="firewatch launch withxbone">
    <navbar-primary />
    <router-view />
  </main>
</template>

<script>
import NavbarPrimary from "./components/navbars/NavbarPrimary.vue";
export default {
  components: { NavbarPrimary },
};
</script>


<style>
</style>
