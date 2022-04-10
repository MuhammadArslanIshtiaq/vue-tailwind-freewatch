<template>
  <main class="media bg-primary relative z-30 text-center pb-32 sm:pb-0">
    <section class="bg-primary relative z-30 container mx-auto px-6">
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

      <div id="maincontain">
        <!-- Nav Buttons -->
        <section class="mt-14 lg:w-4/5 xl:w-11/12 mx-auto">
          <ul class="grid grid-cols-1 md:grid-cols-3 gap-16 md:gap:8">
            <li class="link">
              <router-link
                to="/about"
                class="bg-yellow-sea-600 hover:bg-yellow-sea flex items-center justify-center transition transform hover:scale-105"
              >
                <span class="font-extrabold text-lg uppercase"
                  >About Firewatch</span
                >
              </router-link>
            </li>
            <li class="link active">
              <a
                href
                class="flex items-center justify-center text-yellow-sea border border-yellow-sea"
              >
                <span class="font-extrabold text-lg uppercase"
                  >Screens &amp; Trailers</span
                >
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
        <section class="mb-24">
          <div
            class="mt-16 fullpage flex flex-col md:grid md:grid-cols-2 xl:grid-cols-3 gap-8"
          >
            <div class="videoparent col-span-full">
              <div>
                <div class="h-96 w-full">
                  <iframe
                    class="block h-full w-full"
                    src="https://www.youtube.com/embed/HdUYYnfRdl8?VQ=HD1080"
                    frameborder="0"
                    allowfullscreen=""
                  ></iframe>
                </div>
                <div class="mt-2 text-yellow-sea text-xl flex flex-wrap gap-3">
                  <span class="mr-auto pr-3">Accolades Trailer</span>
                  <span class="opacity-70">September 2016</span>
                </div>
              </div>
            </div>

            <!-- -->

            <div class="gridunit c1 screenshot">
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="http://www.firewatchgame.com/screenshots/firewatch-e3-2.jpg"
                ><img
                  alt="Firewatch screenshot"
                  src="http://www.firewatchgame.com/screenshots/thumbs/firewatch_01.jpg"
              /></a>
            </div>

            <div class="gridunit c1 screenshot">
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="http://www.firewatchgame.com/screenshots/firewatch_150305_06.png"
                ><img
                  alt="Firewatch screenshot"
                  src="http://www.firewatchgame.com/screenshots/thumbs/firewatch_02.jpg"
              /></a>
            </div>

            <div class="gridunit c1 quote">
              <div class="quotecontain">
                <p
                  class="text-yellow-sea tracking-widest text-3xl font-bold leading-tight mb-6"
                >
                  "A beautiful, atmospheric game with a lot of heart."
                </p>
                <p class="font-bold text-yellow-sea-700 text-xl">PC Gamer</p>
              </div>
            </div>

            <!-- -->

            <div class="gridunit c1 screenshot">
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="http://www.firewatchgame.com/screenshots/firewatch-2.jpg"
                ><img
                  alt="Firewatch screenshot"
                  src="http://www.firewatchgame.com/screenshots/thumbs/firewatch_03.jpg"
              /></a>
            </div>

            <div class="gridunit c1 videoparent">
              <div class="videocontain h-full w-full">
                <iframe
                  class="block h-full w-full"
                  src="https://www.youtube.com/embed/qDm2MlcE5u4?VQ=HD1080"
                  frameborder="0"
                  allowfullscreen=""
                ></iframe>
              </div>
            </div>

            <div class="gridunit c1 quote hidetwocolumn">
              <div class="quotecontain">
                <p
                  class="text-yellow-sea tracking-widest text-3xl font-bold leading-tight mb-6"
                >
                  "Firewatch looks completely rad."
                </p>
                <p class="font-bold text-yellow-sea-700 text-xl">
                  Vice Motherboard
                </p>
              </div>
            </div>

            <!-- -->

            <div class="gridunit c1 videoparent">
              <div class="videocontain h-full w-full">
                <iframe
                  class="block h-full w-full"
                  src="https://www.youtube.com/embed/2LgqUiqTvio?VQ=HD1080"
                  frameborder="0"
                  allowfullscreen=""
                ></iframe>
              </div>
            </div>

            <div class="gridunit c1 screenshot">
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="http://www.firewatchgame.com/screenshots/firewatch-e3-5.jpg"
                ><img
                  alt="Firewatch screenshot"
                  src="http://www.firewatchgame.com/screenshots/thumbs/firewatch_04.jpg"
              /></a>
            </div>

            <div class="gridunit c1 videoparent">
              <div class="videocontain h-full w-full">
                <iframe
                  class="block h-full w-full"
                  src="https://www.youtube.com/embed/3v4swVJjuds?VQ=HD1080"
                  frameborder="0"
                  allowfullscreen=""
                ></iframe>
              </div>
            </div>

            <!-- -->

            <div class="gridparent c2 col-span-2">
              <div class="gridunit c2 videoparent h-full w-full">
                <div class="videocontain h-full w-full">
                  <iframe
                    class="block h-full w-full"
                    src="https://www.youtube.com/embed/cXWlgP5hZzc?VQ=HD1080"
                    frameborder="0"
                    allowfullscreen=""
                  ></iframe>
                </div>
                <div class="videocaptions hideonecolumn">
                  <span class="left">Trailer 2</span>
                  <span class="right gridcaptionbold">E3 2015</span>
                </div>
              </div>
            </div>

            <div class="flex flex-col gap-8">
              <div class="gridunit c1 screenshot">
                <a
                  href="http://www.firewatchgame.com/screenshots/firewatch-e3-6.jpg"
                  ><img
                    alt="Firewatch screenshot"
                    src="http://www.firewatchgame.com/screenshots/thumbs/firewatch_05.jpg"
                /></a>
              </div>
              <div class="gridunit c1 screenshot">
                <a
                  href="http://www.firewatchgame.com/screenshots/firewatch-e3-4.jpg"
                  ><img
                    alt="Firewatch screenshot"
                    src="http://www.firewatchgame.com/screenshots/thumbs/firewatch_06.jpg"
                /></a>
              </div>
            </div>

            <!-- -->

            <div class="gridparent c1">
              <div class="gridunit c1 quote">
                <div class="quotecontain mb-16">
                  <p
                    class="text-yellow-sea tracking-widest text-4xl font-bold leading-tight mb-6"
                  >
                    "A fresh,<br />
                    clever take on adventure gaming."
                  </p>
                  <p class="font-bold text-yellow-sea-700 text-xl">GameSpot</p>
                </div>
              </div>
              <div class="gridunit c1 quote">
                <div class="quotecontain">
                  <p
                    class="text-yellow-sea tracking-widest text-4xl font-bold leading-tight mb-6"
                  >
                    "Traps you between suspense and beauty…"
                  </p>
                  <p class="font-bold text-yellow-sea-700 text-xl">
                    Kill Screen
                  </p>
                </div>
              </div>
            </div>

            <div class="gridunit c2 videoparent col-span-2">
              <div class="videocontain h-full w-full">
                <iframe
                  class="block h-full w-full"
                  src="https://www.youtube.com/embed/d02lhvvVSy8?VQ=HD1080"
                  frameborder="0"
                  allowfullscreen=""
                ></iframe>
              </div>
              <div class="videocaptions hideonecolumn">
                <span class="left">Trailer 1</span>
                <span class="right gridcaptionbold">PAX 2014</span>
              </div>
            </div>

            <!-- -->

            <div class="gridunit c1 screenshot">
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="http://www.firewatchgame.com/screenshots/firewatch_150305_05.png"
                ><img
                  alt="Firewatch screenshot"
                  src="http://www.firewatchgame.com/screenshots/thumbs/firewatch_07.jpg"
              /></a>
            </div>

            <div class="gridunit c1 videoparent">
              <div class="videocontain h-full w-full">
                <iframe
                  class="block h-full w-full"
                  src="https://www.youtube.com/embed/fdeSd4yNLuM?VQ=HD1080"
                  frameborder="0"
                  allowfullscreen=""
                ></iframe>
              </div>
            </div>

            <div class="gridunit c1 screenshot">
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="http://www.firewatchgame.com/screenshots/firewatch-e3-1.jpg"
                ><img
                  alt="Firewatch screenshot"
                  src="http://www.firewatchgame.com/screenshots/thumbs/firewatch_08.jpg"
              /></a>
            </div>

            <!-- -->

            <div class="gridunit c1 screenshot">
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="http://www.firewatchgame.com/screenshots/Bear-Tree-Approach-3.jpg"
                ><img
                  alt="Firewatch screenshot"
                  src="http://www.firewatchgame.com/screenshots/thumbs/firewatch_09.jpg"
              /></a>
            </div>

            <div class="gridunit c1 screenshot">
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="http://www.firewatchgame.com/screenshots/firewatch_150305_01.png"
                ><img
                  alt="Firewatch screenshot"
                  src="http://www.firewatchgame.com/screenshots/thumbs/firewatch_10.jpg"
              /></a>
            </div>

            <div class="gridunit c1 screenshot">
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="http://www.firewatchgame.com/about/about_feature_02@2x.jpg"
                ><img
                  alt="Firewatch screenshot"
                  src="http://www.firewatchgame.com/screenshots/thumbs/firewatch_11.jpg"
              /></a>
            </div>

            <!-- -->

            <div class="gridunit c3 videoparent col-span-full h-96">
              <div class="videocontain h-full w-full">
                <iframe
                  class="block h-full w-full"
                  src="https://www.youtube.com/embed/T-qmLZfMvKU?VQ=HD1080"
                  frameborder="0"
                  allowfullscreen=""
                ></iframe>
              </div>
              <div class="mt-2 text-yellow-sea text-xl flex flex-wrap gap-3">
                <span class="mr-auto pr-3"
                  >Nintendo Switch Release Trailer</span
                >
                <span class="opacity-70">December 2018</span>
              </div>
            </div>
          </div>
        </section>
        <!-- footer -->

        <footer-primary />

        <!-- end footer -->
      </div>
    </section>
  </main>
</template>

<script>
import FooterPrimary from "../components/footers/FooterPrimary.vue";
export default {
  components: { FooterPrimary },
};
</script>

<style></style>
