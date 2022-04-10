<template>
  <section>
    <div class="keyart" id="nonparallax"></div>
    <div class="keyart" id="parallax">
      <div
        class="keyart_layer parallax"
        id="keyart-0"
        data-speed="2"
        style="transform: translate3d(0px, 0px, 0px)"
      ></div>
      <!-- 00.0 -->
      <div
        class="keyart_layer parallax"
        id="keyart-1"
        data-speed="5"
        style="transform: translate3d(0px, 0px, 0px)"
      ></div>
      <!-- 12.5 -->
      <div
        class="keyart_layer parallax"
        id="keyart-2"
        data-speed="11"
        style="transform: translate3d(0px, 0px, 0px)"
      ></div>
      <!-- 25.0 -->
      <div
        class="keyart_layer parallax"
        id="keyart-3"
        data-speed="16"
        style="transform: translate3d(0px, 0px, 0px)"
      ></div>
      <!-- 37.5 -->
      <div
        class="keyart_layer parallax"
        id="keyart-4"
        data-speed="26"
        style="transform: translate3d(0px, 0px, 0px)"
      ></div>
      <!-- 50.0 -->
      <div
        class="keyart_layer parallax"
        id="keyart-5"
        data-speed="36"
        style="transform: translate3d(0px, 0px, 0px)"
      ></div>
      <!-- 62.5 -->
      <div
        class="keyart_layer parallax"
        id="keyart-6"
        data-speed="49"
        style="transform: translate3d(0px, 0px, 0px)"
      ></div>
      <!-- 75.0 -->
      <div class="keyart_layer" id="keyart-scrim"></div>
      <div
        class="keyart_layer parallax"
        id="keyart-7"
        data-speed="69"
        style="transform: translate3d(0px, 0px, 0px)"
      ></div>
      <!-- 87.5 -->
      <div class="keyart_layer" id="keyart-8" data-speed="100"></div>
      <!-- 100. -->
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
/* PARALLAX */

.keyart,
.keyart_layer {
  height: 1000px;
}

#parallax {
  display: none;
}
#nonparallax {
  display: block;
}

#nonparallax {
  background-image: url("../../assets/images/keyart-mobile.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: auto 100%;
}

.keyart {
  position: relative;
  z-index: 10;
}

.keyart_layer {
  background-position: bottom center;
  background-size: auto 1038px;
  background-repeat: repeat-x;
  width: 100%;
  position: absolute;
}
.keyart_layer.parallax {
  position: fixed;
}
#keyart-0 {
  background-image: url("../../assets/images/parallax/parallax0.png");
  background-color: #ffaf1b;
}
#keyart-1 {
  background-image: url("../../assets/images/parallax/parallax1.png");
}
#keyart-2 {
  background-image: url("../../assets/images/parallax/parallax2.png");
}
#keyart-3 {
  background-image: url("../../assets/images/parallax/parallax3.png");
}
#keyart-4 {
  background-image: url("../../assets/images/parallax/parallax4.png");
}
#keyart-5 {
  background-image: url("../../assets/images/parallax/parallax5.png");
}
#keyart-6 {
  background-image: url("../../assets/images/parallax/parallax6.png");
}
#keyart-7 {
  background-image: url("../../assets/images/parallax/parallax7.png");
}
#keyart-8 {
  background-image: url("../../assets/images/parallax/parallax8.png");
}
#keyart-scrim {
  background-color: #ffaf00;
  opacity: 0;
}

/********************/
/********************/
/* ENABLES PARALLAX */
/********************/
/********************/

@media (min-width: 601px) {
  #nonparallax {
    display: none;
  }
  #parallax {
    display: block;
  }
}

/*********************/
/*********************/
/* DISABLES PARALLAX */
/*********************/
/*********************/

@media (max-width: 600px) {
  #nonparallax {
    display: block;
  }
  #parallax {
    display: none;
  }
}

/* PARALLAX */

@media only screen and (max-device-width: 450px) {
  /* PARALLAX */

  .keyart,
  .keyart_layer {
    height: 550px;
  }

  .keyart_layer {
    position: absolute;
    background-size: auto 600px;
  }
}
</style>