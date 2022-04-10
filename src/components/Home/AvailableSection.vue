<template>
  <div
    id="maincontain"
    class="bg-primary relative z-30 text-center pb-32 sm:pb-0"
  >
    <div id="main" class="bg-primary relative z-30 container mx-auto px-6">
      <div class="text-yellow-sea">
        <h2 class="text-4xl font-bold tracking-widest">
          <span>Available now for</span> $19.99
        </h2>
      </div>

      <section class="mt-7 lg:w-4/5 xl:w-1/2 mx-auto">
        <ul class="grid grid-cols-1 sm:grid-cols-2 gap-8">
          <li>
            <a
              class="
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
              href="#"
            >
              <span class="block h-5">
                <img
                  class="block h-full w-full"
                  src="../../assets/images/buyicon_pc.png"
                />
              </span>
              <span class="ml-3 font-extrabold text-lg">Windows Mac Linux</span>
            </a>
          </li>
          <li>
            <a
              class="
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
              href="#"
            >
              <span class="block h-5">
                <img
                  class="block h-full w-full"
                  src="../../assets/images/buyicon_switch.png"
                />
              </span>
              <span class="ml-3 font-extrabold text-lg">Nintendo Switch</span>
            </a>
          </li>
          <li>
            <a
              class="
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
              href="#"
            >
              <span class="block h-5">
                <img
                  class="block h-full w-full"
                  src="../../assets/images/buyicon_ps4.png"
                />
              </span>
              <span class="ml-3 font-extrabold text-lg">PlayStation 4</span>
            </a>
          </li>
          <li>
            <a
              class="
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
              href="#"
            >
              <span class="block h-5">
                <img
                  class="block h-full w-full"
                  src="../../assets/images/buyicon_xbone.png"
                />
              </span>
              <span class="ml-3 font-extrabold text-lg">Xbox One</span>
            </a>
          </li>
        </ul>
      </section>

      <section class="mt-20 lg:w-4/5 xl:w-2/3 mx-auto">
        <div class="h-96 w-full">
          <iframe
            class="h-full w-full"
            src="https://www.youtube-nocookie.com/embed/cXWlgP5hZzc"
            frameborder="0"
            allowfullscreen=""
          ></iframe>
        </div>
      </section>

      <section class="mt-20 lg:w-4/5 xl:w-1/2 mx-auto text-yellow-sea">
        <h5 class="text-2xl font-bold leading-9 mb-8 text-left">
          Firewatch is a mystery set in the Wyoming wilderness, where your only
          emotional lifeline is the person on the other end of a handheld radio.
        </h5>
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-8 text-left">
          <p>
            The year is 1989. <br /><br />
            You are a man named Henry who has retreated from your messy life to
            work as a fire lookout in the Wyoming wilderness. Perched atop a
            mountain, it's your job to find smoke and keep the wilderness safe.
            <br /><br />
            An especially hot, dry summer has everyone on edge. Your supervisor,
            a woman named Delilah, is available to you
          </p>
          <p>
            at all times over a small, handheld radio—and is your only contact
            with the world you've left behind. <br /><br />
            But when something strange draws you out of your lookout tower and
            into the world below, you'll explore a wild and unknown environment,
            facing questions and making interpersonal choices that can build or
            destroy the only meaningful relationship you have.
          </p>
        </div>
      </section>

      <section class="mt-10 lg:w-4/5 xl:w-1/2 mx-auto">
        <ul class="grid grid-cols-1 sm:grid-cols-2 gap-8">
          <li class="link media">
            <router-link
              to="/media"
              class="
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
                >Screens &amp; Trailers</span
              >
            </router-link>
          </li>
          <li class="link faq">
            <router-link
              to="/about"
              class="
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
                >Firewatch FAQ</span
              >
            </router-link>
          </li>
        </ul>
      </section>

      <section class="mt-16 lg:w-4/5 xl:w-2/3 mx-auto">
        <ul class="grid grid-cols-2 gap-4 md:gap-8">
          <li>
            <a
              target="_blank"
              rel="noopener noreferrer"
              href="https://www.firewatchgame.com/screenshots/firewatch-e3-2.jpg"
              ><img
                alt="Firewatch screenshot"
                src="../../assets/images/firewatch_01.jpg"
            /></a>
          </li>
          <li>
            <a
              target="_blank"
              rel="noopener noreferrer"
              href="https://www.firewatchgame.com/screenshots/firewatch_150305_06.png"
              ><img
                alt="Firewatch screenshot"
                src="../../assets/images/firewatch_02.jpg"
            /></a>
          </li>
          <li>
            <a
              target="_blank"
              rel="noopener noreferrer"
              href="https://www.firewatchgame.com/screenshots/firewatch-2.jpg"
              ><img
                alt="Firewatch screenshot"
                src="../../assets/images/firewatch_03.jpg"
            /></a>
          </li>
          <li>
            <a
              target="_blank"
              rel="noopener noreferrer"
              href="https://www.firewatchgame.com/screenshots/firewatch-e3-5.jpg"
              ><img
                alt="Firewatch screenshot"
                src="../../assets/images/firewatch_04.jpg"
            /></a>
          </li>
        </ul>
      </section>

      <section class="mt-10 lg:w-4/5 xl:w-1/2 mx-auto">
        <h2
          class="
            text-yellow-sea
            tracking-widest
            text-4xl
            font-bold
            leading-tight
            mb-6
          "
        >
          "As visually striking <br />as its unique premise."
        </h2>
        <h3 class="font-bold text-yellow-sea-700 text-xl">
          Entertainment Weekly
        </h3>
      </section>

      <footer-primary />
    </div>
  </div>
</template>

<script>
import FooterPrimary from "../footers/FooterPrimary.vue";
export default {
  components: { FooterPrimary },
};
</script>

<style scoped>
</style>
