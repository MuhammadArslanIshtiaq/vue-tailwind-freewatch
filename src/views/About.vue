<template>
  <main class="bg-primary relative z-30 text-center pb-32 sm:pb-0">
    <!-- Logo -->
    <div class="pt-16">
      <router-link to="/" class="block w-60 md:w-96 mx-auto">
        <img
          class="block h-full w-full"
          id="firewatchlogoimg"
          alt="Firewatch logo"
          src="../assets/images/firewatch_subpage_mainlogo@2x.png"
        />
      </router-link>
    </div>
    <div>
      <!-- Nav Buttons -->
      <section class="my-14 lg:w-4/5 xl:w-11/12 mx-auto">
        <ul class="grid grid-cols-1 md:grid-cols-3 gap-16 md:gap:8">
          <li class="link">
            <router-link
              to="/media"
              class="bg-yellow-sea-600 hover:bg-yellow-sea flex items-center justify-center transition transform hover:scale-105"
            >
              <span class="font-extrabold text-lg uppercase"
                >Screens &amp; Trailers</span
              >
            </router-link>
          </li>
          <li class="link active">
            <a
              href
              class="flex items-center justify-center text-yellow-sea border border-yellow-sea"
            >
              <span class="font-extrabold text-lg uppercase"
                >About Firewatch
              </span>
            </a>
          </li>
          <li class="link">
            <router-link
              to="/"
              class="bg-yellow-sea-600 hover:bg-yellow-sea flex items-center justify-center transition transform hover:scale-105"
            >
              <span class="font-extrabold text-lg uppercase">Home</span>
            </router-link>
          </li>
        </ul>
      </section>

      <!-- Main Content -->

      <div class="relative px-4 sm:px-6 lg:px-8 my-24">
        <div class="text-lg max-w-prose mx-auto text-left">
          <h1>
            <span
              class="mt-2 block leading-8 font-extrabold tracking-tight text-yellow-sea text-xl sm:text-2xl"
              >Tell me about Firewatch!</span
            >
          </h1>

          <p class="mt-8 text-base text-yellow-sea leading-8">
            Firewatch is a single-player first-person video game where you, as a
            man named Henry, explore the Wyoming wilderness after taking a
            summer job as a fire lookout. What is supposed to be a peaceful
            respite from your complicated life takes a turn when you start to
            question some of the things that are happening to you.
          </p>
          <p class="mt-8 text-base text-yellow-sea leading-8">
            Your only human connection is over a handheld radio, which you’ll
            use to speak with your supervisor Delilah about the things both of
            you are experiencing.
          </p>
        </div>
      </div>

      <div class="w-5/6 mx-auto">
        <img
          src="http://www.firewatchgame.com/about/about_feature_01.jpg"
          srcset="
            http://www.firewatchgame.com/about/about_feature_01@2x.jpg 2740w
          "
          alt="Firewatch"
        />
      </div>

      <div class="relative px-4 sm:px-6 lg:px-8 my-24">
        <div class="text-lg max-w-prose mx-auto text-left">
          <h1>
            <span
              class="mt-2 block leading-8 font-extrabold tracking-tight text-yellow-sea text-xl sm:text-2xl"
              >Well, that's a real tease.</span
            >
          </h1>

          <p class="mt-8 text-base text-yellow-sea leading-8">
            Firewatch is incredibly story driven! To tell you more would be to
            deprive you of the joy of discovery. You’re going to forge a living,
            breathing relationship and uncover a tense, unexpected mystery.
          </p>

          <h1>
            <span
              class="mt-2 block leading-8 font-extrabold tracking-tight text-yellow-sea text-xl sm:text-2xl"
              >I’m not here to learn about Firewatch. I’ve got a problem with my
              copy of the game! Or my in-game photos!</span
            >
          </h1>

          <p class="mt-8 text-base text-yellow-sea leading-8">
            Please visit
            <a href="" class="font-bold underline hover:text-white"
              >our support website.</a
            >
          </p>
        </div>
      </div>

      <div class="w-5/6 mx-auto">
        <img
          src="http://www.firewatchgame.com/about/about_feature_02.jpg"
          srcset="
            http://www.firewatchgame.com/about/about_feature_02@2x.jpg 2740w
          "
          alt="Firewatch"
        />
      </div>

      <div class="relative px-4 sm:px-6 lg:px-8 my-24">
        <div class="text-lg max-w-prose mx-auto text-left">
          <h1>
            <span
              class="mt-2 block leading-8 font-extrabold tracking-tight text-yellow-sea text-xl sm:text-2xl"
              >Well, that's a real tease.</span
            >
          </h1>

          <p class="mt-8 text-base text-yellow-sea leading-8">
            Firewatch is incredibly story driven! To tell you more would be to
            deprive you of the joy of discovery. You’re going to forge a living,
            breathing relationship and uncover a tense, unexpected mystery.
          </p>

          <h1>
            <span
              class="mt-2 block leading-8 font-extrabold tracking-tight text-yellow-sea text-xl sm:text-2xl"
              >I’m not here to learn about Firewatch. I’ve got a problem with my
              copy of the game! Or my in-game photos!</span
            >
          </h1>

          <p class="mt-8 text-base text-yellow-sea leading-8">
            Please visit
            <a href="" class="font-bold underline hover:text-white"
              >our support website.</a
            >
          </p>
        </div>
      </div>

      <!-- footer -->

      <footer-primary />

      <!-- end footer -->
    </div>
  </main>
</template>

<script>
import FooterPrimary from "../components/footers/FooterPrimary.vue";
export default {
  components: { FooterPrimary },
};
</script>

<style></style>
