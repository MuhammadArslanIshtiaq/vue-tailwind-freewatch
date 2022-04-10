<template>
  <nav
    class="
      bg-black
      fixed
      bottom-0
      sm:sticky sm:top-0 sm:bottom-auto
      z-50
      w-full
    "
  >
    <div class="container w-11/12 mx-auto">
      <ul class="text-center sm:flex flex-wrap gap-2">
        <li class="mr-auto">
          <router-link
            to="/"
            class="block text-yellow-sea-400 hover:text-yellow-sea px-3 py-2"
            ><strong>Campo Santo</strong></router-link
          >
        </li>

        <li>
          <router-link
            to="/"
            class="
              block
              text-yellow-sea
              bg-yellow-sea-600
              active:bg-yellow-sea-600
              hover:bg-yellow-sea-700
              px-3
              py-2
            "
            ><strong>Firewatch</strong></router-link
          >
        </li>
        <li>
          <a
            href="#"
            class="
              block
              text-yellow-sea
              active:bg-yellow-sea-600
              hover:bg-yellow-sea-700
              px-3
              py-2
            "
            ><strong><span>Development </span>Blog</strong></a
          >
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
</style>