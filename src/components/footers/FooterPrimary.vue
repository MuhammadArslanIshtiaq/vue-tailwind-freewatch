<template>
  <footer>
    <section class="mt-10 lg:w-4/5 xl:w-2/3 mx-auto">
      <ul class="flex flex-wrap gap-6 sm:items-center">
        <li class="flex-1">
          <a
            href="#"
            class="
              h-full
              bg-yellow-sea-600
              hover:bg-yellow-sea
              flex
              items-center
              justify-center
              p-1
              transition
              transform
              hover:scale-105
            "
          >
            <span class="font-extrabold text-md tracking-widest"
              >Tech Support</span
            >
          </a>
        </li>
        <li class="hidden sm:block">
          <span class="block h-16 w-16">
            <img
              class="block h-full w-full"
              src="../../assets/images/firewatch_shield_small.png"
              alt="...."
            />
          </span>
        </li>
        <li class="flex-1">
          <a
            href="#"
            class="
              h-full
              bg-yellow-sea-600
              hover:bg-yellow-sea
              flex
              items-center
              justify-center
              p-1
              transition
              transform
              hover:scale-105
            "
          >
            <span class="font-extrabold text-md tracking-widest"
              ><span>Streaming &amp; Let's Plays</span></span
            >
          </a>
        </li>
      </ul>
    </section>

    <section class="my-8 lg:w-4/5 xl:w-2/3 mx-auto">
      <a href="#" class="font-bold text-yellow-sea hover:text-white text-xl"
        >日本語に関する情報</a
      >
    </section>

    <!-- End Temporary Japan Block -->

    <section
      class="mb-10 text-yellow-sea-700 text-lg lg:w-4/5 xl:w-2/3 mx-auto"
    >
      <p>
        ©<span id="year">2022</span> Campo Santo, in cooperation with Panic.
      </p>
      <p>Firewatch is a trademark of Campo Santo.</p>
      <p>Nintendo Switch is a trademark of Nintendo.</p>
    </section>

    <section class="pb-16 lg:w-4/5 xl:w-2/3 mx-auto">
      <ul class="flex justify-center items-start gap-12">
        <li>
          <a
            target="_blank"
            rel="noopener noreferrer"
            href="http://www.camposanto.com/"
          >
            <span class="block h-20 w-20">
              <img
                class="
                  block
                  h-full
                  w-full
                  bg-yellow-sea-700
                  hover:bg-yellow-sea
                "
                src="../../assets/images/logo_camposanto_transparent.png"
                alt="...."
              />
            </span>
          </a>
        </li>
        <li>
          <a
            target="_blank"
            rel="noopener noreferrer"
            href="https://www.panic.com"
          >
            <span class="block h-20 w-20">
              <img
                class="
                  block
                  h-full
                  w-full
                  bg-yellow-sea-700
                  hover:bg-yellow-sea
                "
                src="../../assets/images/logo_panic_transparent.png"
                alt="...."
              />
            </span>
          </a>
        </li>
      </ul>
    </section>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.japan-block {
  font-family: "Noto Sans CJK JP", sans-serif;
  font-size: 26px;
  letter-spacing: 4px;
  margin-top: 40px;
}

.japan-block a:hover {
  color: #ffffff;
}
</style>