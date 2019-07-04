<template>
  <div>
    <div class="header">
      <ul class="sidenav" id="mobile-demo">
        <li>
          <a href="sass.html">Sass</a>
        </li>
        <li>
          <a href="badges.html">Components</a>
        </li>
        <li>
          <a href="collapsible.html">Javascript</a>
        </li>
        <li>
          <a href="mobile.html">Mobile</a>
        </li>
      </ul>

      <div class="container">
        <div class="header-flex">
          <div class="header__logo flex-header-item">SITE LOGO</div>

          <div
            class="col hide-on-large-only sidenav-trigger"
            style="position:fixed; top: 10px; left: 0px;"
            data-target="mobile-demo"
          >
            <div class="header__menu">
              <a href="#">
                <div class="header__menu__item header__menu__item--rounded">
                  <i class="material-icons">format_align_justify</i>
                </div>
              </a>
            </div>
          </div>

          <div class="header__menu flex-header-item">
            <div class="row">
              <div class="col hide-on-med-and-down">
                <a href="#">
                  <div class="header__menu__item header__menu__item--rounded">Menu item1</div>
                </a>
                <a href="#">
                  <div class="header__menu__item header__menu__item--rounded">Menu item2</div>
                </a>
                <a href="#">
                  <div class="header__menu__item header__menu__item--rounded">Menu item3</div>
                </a>
                <a href="#">
                  <div class="header__menu__item header__menu__item--rounded">Menu item4</div>
                </a>
              </div>
            </div>
          </div>

          <div class="header__menu flex-header-item">
            <el-dropdown>
              <div class="header__avatar">
                <img src="https://www.w3schools.com/howto/img_avatar.png" alt />
              </div>
              <el-dropdown-menu slot="dropdown">DFJKASD;LFJASDLF</el-dropdown-menu>
            </el-dropdown>
          </div>
        </div>
      </div>
    </div>

    <div class="shaped-section"></div>

    <div class="section">
      <div class="section__info">
        <div class="container">
          <div class="row wow zoomIn">
            <div class="section__info__product">
              <div class="col m5 s12 l5">
                <div
                  class="section__info__product__img section__info__product__img--rounded z-depth-5"
                >
                  <img src="http://localhost:8080/img.jpg" alt />
                </div>
              </div>

              <div class="col m7 s12 l7">
                <div class="section__info__product__info">
                  <div class="section__info__product__info__desc">Only available for 24 hours</div>
                  <div class="section__info__product__info__title">Amazing template already on sale</div>
                  <div class="button button--rounded button--bordered">Buy for $399</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="section">
      <div class="container">
        <div class="section__content section__content--small">
          <div class="row flex">
            <div
              class="disintegration-target wow fadeInLeftBig flex-card-item section__info__product__img section__info__product__img--rounded z-depth-5"
            >
              <img src="http://localhost:8080/img.jpg" alt />
            </div>
            <div
              class="disintegration-target wow fadeInRightBig flex-card-item section__info__product__img section__info__product__img--rounded z-depth-5"
            >
              <img src="http://localhost:8080/img.jpg" alt />
            </div>
            <div
              class="disintegration-target wow fadeInLeftBig flex-card-item section__info__product__img section__info__product__img--rounded z-depth-5"
            >
              <img src="http://localhost:8080/img.jpg" alt />
            </div>
            <div
              class="disintegration-target wow fadeInRightBig flex-card-item section__info__product__img section__info__product__img--rounded z-depth-5"
            >
              <img src="http://localhost:8080/img.jpg" alt />
            </div>
            <div
              class="disintegration-targetwow fadeInLeftBig flex-card-item section__info__product__img section__info__product__img--rounded z-depth-5"
            >
              <img src="http://localhost:8080/img.jpg" alt />
            </div>
            <div
              class="disintegration-target wow fadeInRightBig flex-card-item section__info__product__img section__info__product__img--rounded z-depth-5"
            >
              <img src="http://localhost:8080/img.jpg" alt />
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="parallax-container">
      <div class="parallax-layout">
        <div class="container">
          <div class="section">
            <div class="section__content center-align">
              <div class="out-of-the-box-img">
                <img class="z-depth-5" src="http://localhost:8080/img.jpg" alt />
              </div>

              <div
                class="section__content__title section__content__title--large section__content__title--white"
              >Lorem ipsum dolor sit amet.</div>
              <div
                class="section__content__desc section__content__desc--size_m section__content__desc--white"
              >Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates ipsam eligendi saepe animi incidunt qui itaque voluptate vero aliquid aliquam. Deserunt labore, beatae deleniti fugiat magni culpa. Aperiam, nostrum libero.</div>
            </div>
          </div>
        </div>
        <div class="parallax">
          <img
            src="https://www.androidguys.com/wp-content/uploads/2018/07/abstraction_sharp_figure_101902_1600x1200.jpg"
          />
        </div>
      </div>
    </div>

    <div class="section">
      <div class="container section__content">
        <img id="disappear" style="border-radius:5px" src="http://localhost:8080/trump.jpg" />
        <a href="#" @click.prevent="disintegrate()">DELETE DONAL TRUMP</a>
        <a href="#" @click.prevent="unsnap()">UNSNAP</a>
      </div>
    </div>

    <div class="section section--seagreen">
      <div class="container section__content">
        <div class="testBlock"></div>
      </div>
    </div>

    <div class="section section--grey">
      <div class="container">
        <div class="section__content">
          <div
            class="section__content__title section__content__title--large section__content__title--black"
          >SOMETHING NEW</div>

          <div class="row flex">
            <div class="item-card z-depth-5">
              <div class="item-card__img">
                <img
                  src="https://www.androidguys.com/wp-content/uploads/2018/07/abstraction_sharp_figure_101902_1600x1200.jpg"
                  alt
                />
              </div>
            </div>

            <div class="item-card z-depth-5">
              <div class="item-card__img">
                <img
                  src="https://www.androidguys.com/wp-content/uploads/2018/07/abstraction_sharp_figure_101902_1600x1200.jpg"
                  alt
                />
              </div>
            </div>

            <div class="item-card z-depth-5">
              <div class="item-card__img">
                <img
                  src="https://www.androidguys.com/wp-content/uploads/2018/07/abstraction_sharp_figure_101902_1600x1200.jpg"
                  alt
                />
              </div>
            </div>

            <div class="item-card z-depth-5">
              <div class="item-card__img">
                <img
                  src="https://www.androidguys.com/wp-content/uploads/2018/07/abstraction_sharp_figure_101902_1600x1200.jpg"
                  alt
                />
              </div>
            </div>

            <div class="item-card z-depth-5">
              <div class="item-card__img">
                <img
                  src="https://www.androidguys.com/wp-content/uploads/2018/07/abstraction_sharp_figure_101902_1600x1200.jpg"
                  alt
                />
              </div>
            </div>

            <div class="item-card z-depth-5">
              <div class="item-card__img">
                <img
                  src="https://www.androidguys.com/wp-content/uploads/2018/07/abstraction_sharp_figure_101902_1600x1200.jpg"
                  alt
                />
              </div>
            </div>

            <div class="item-card z-depth-5">
              <div class="item-card__img">
                <img
                  src="https://www.androidguys.com/wp-content/uploads/2018/07/abstraction_sharp_figure_101902_1600x1200.jpg"
                  alt
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="section">
      <Slider style="height:400px;" :indicators="false" :touch="true" animation="fade">
        <Slider-item v-for="(i, index) in list" :key="index" :style="i"></Slider-item>
      </Slider>
    </div>

    <div class="section">
      <vue-particles
        style="height:400px;"
        color="#27ae60"
        linesColor="#27ae60"
        :particleSize="4"
        shapeType="circle"
        :particlesNumber="150"
      ></vue-particles>
      <div class="container" style="margin-top:-360px;">
        <div class="section__content center-align">
          <div
            class="section__content__title section__content__title--large section__content__title--black"
          >Lorem ipsum dolor sit amet.</div>
          <div
            class="section__content__desc section__content__desc--size_m section__content__desc--black"
          >Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates ipsam eligendi saepe animi incidunt qui itaque voluptate vero aliquid aliquam. Deserunt labore, beatae deleniti fugiat magni culpa. Aperiam, nostrum libero.</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { Slider, SliderItem } from "vue-easy-slider";

import WOW from "wow.js";

export default {
  name: "app",

  components: {
    Slider,
    SliderItem
  },

  data() {
    return {
      sliderIndex: 1,
      list: [
        { backgroundColor: "#8e44ad", width: "100%", height: "100%" },
        { backgroundColor: "#f1c40f", width: "100%", height: "100%" },
        { backgroundColor: "#2f3640", width: "100%", height: "100%" }
      ],
      userIconClicked: false
    };
  },
  computed: {
    audio() {
      return new Audio("snap.mp3");
    }
  },
  methods: {
    moveToIndex(index) {
      this.sliderIndex = index;
    },

    generateFrames($canvas, count = 32) {
      const REPETITION_COUNT = 4;

      const { width, height } = $canvas;
      const ctx = $canvas.getContext("2d");
      const originalData = ctx.getImageData(0, 0, width, height);
      const imageDatas = [...Array(count)].map((_, i) =>
        ctx.createImageData(width, height)
      );

      for (let x = 0; x < width; ++x) {
        for (let y = 0; y < height; ++y) {
          for (let i = 0; i < REPETITION_COUNT; ++i) {
            const dataIndex = Math.floor(
              (count * (Math.random() + (2 * x) / width)) / 3
            );
            const pixelIndex = (y * width + x) * 4;
            for (let offset = 0; offset < 4; ++offset) {
              imageDatas[dataIndex].data[pixelIndex + offset] =
                originalData.data[pixelIndex + offset];
            }
          }
        }
      }

      return imageDatas.map(data => {
        const $c = $canvas.cloneNode(true);
        $c.getContext("2d").putImageData(data, 0, 0);
        return $c;
      });
    },

    replaceElementVisually($old, $new) {
      const $parent = $old.offsetParent;
      $new.style.top = `${$old.offsetTop}px`;
      $new.style.left = `${$old.offsetLeft}px`;
      $new.style.width = `${$old.offsetWidth}px`;
      $new.style.height = `${$old.offsetHeight}px`;
      $parent.appendChild($new);
      $old.style.visibility = "hidden";
    },

    unsnap() {
      document.getElementById("disappear").style.visibility = "visible";
    },

    disintegrate($elm) {
      const NUM_FRAMES = 128;

      $elm = document.getElementById("disappear");

      html2canvas($elm).then($canvas => {
        this.audio.play();

        setTimeout(() => {
          const $container = document.createElement("div");
          $container.classList.add("disintegration-container");

          const $frames = this.generateFrames($canvas, NUM_FRAMES);
          $frames.forEach(($frame, i) => {
            $frame.style.transitionDelay = `${(1.35 * i) / $frames.length}s`;
            $container.appendChild($frame);
          });

          this.replaceElementVisually($elm, $container);

          $container.offsetLeft;
          $frames.forEach($frame => {
            const randomRadian = 2 * Math.PI * (Math.random() - 0.5);
            $frame.style.transform = `rotate(${15 *
              (Math.random() - 0.5)}deg) translate(${60 *
              Math.cos(randomRadian)}px, ${30 * Math.sin(randomRadian)}px)
rotate(${15 * (Math.random() - 0.5)}deg)`;
            $frame.style.opacity = 0;
          });
        }, 1000);
      });
    }
  },

  mounted() {
    $(".sidenav").sidenav();
    $(".parallax").parallax();
    var wow = new WOW();
    wow.init();

    let header = document.getElementsByClassName("header")[0];

    window.onscroll = function() {
      var scrolled = window.pageYOffset || document.documentElement.scrollTop;
      if (scrolled > 75) {
        header.classList.add("header--darken");
      } else {
        header.classList.remove("header--darken");
      }
    };
  }
};
</script>

<style lang="scss">
.testBlock {
  width: 200px;
  height: 200px;
  animation-name: animation;

  background-image: radial-gradient(at top left, #5b4ffc, #df0253);

  box-shadow: 6px 6px black,
            18px 12px red;

}

@keyframes animation {
  from {
    box-shadow: 6px 6px black,
            12px 12px red;
  }
  50% {
    box-shadow: 6px 6px green,
            12px 12px yellow;
  }
  to {
    box-shadow: 6px 6px grey,
            12px 12px blue;
  }
}

.testBlock:hover {
  animation-duration: 1000ms;
  animation-delay: 0ms;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
  animation-fill-mode: forwards;
}

.disintegration-container {
  position: absolute;
  pointer-events: none;

  > canvas {
    position: absolute;
    left: 0;
    top: 0;
    transition: transform 1s ease-out, opacity 1s ease-out;
    opacity: 1;
    transform: rotate(0deg) translate(0px, 0px) rotate(0deg);
  }
}

@keyframes debug-pulse {
  0% {
    filter: none;
  }
  95% {
    filter: none;
  }
  95% {
    filter: drop-shadow(0 1px 0 rgba(255, 0, 0, 1));
  }
  100% {
    filter: drop-shadow(0 1px 0 rgba(255, 0, 0, 1));
  }
}

.item {
  max-width: 60ch;
  background: #fff;
  margin-bottom: 1em;
  padding: 1em;
  border-radius: 5px;
  border: 1px solid #ddd;

  h1 {
    margin-top: 0;
  }
  p {
    margin-bottom: 0;
  }
  img {
    float: right;
  }
}

@mixin inline {
  display: inline-block;
  vertical-align: middle;
}

.sidenav {
  z-index: 999;
}

.slider-btn {
  z-index: 998 !important;
}

.shaped-section {
  position: absolute;
  height: 550px;
  width: 100%;
  background: linear-gradient(150deg, #7795f8 15%, #6772e5 70%, #555abf 94%);
  -webkit-transform: skewY(-8deg);
  transform: skewY(-8deg);
  -webkit-transform-origin: 0;
  transform-origin: 0;
}

.out-of-the-box-img {
  background: rgba(0, 0, 0, 0.3);
  border-radius: 10px;
  padding-bottom: 0px;
  margin-bottom: 50px;
  width: 300px;
  display: inline-block;

  &:hover {
    padding-bottom: 15px;
  }

  &:hover img {
    margin-left: 15px;
    margin-top: -15px;
  }

  & img {
    position: relative;
    border-radius: 10px;
    width: 300px;
  }
}

.parallax-layout {
  background: rgba(0, 0, 0, 0.5);
  width: 100%;
  height: 100%;
}

.parallax-container {
  height: auto;
}

body {
  margin: 0;
  overflow-x: hidden;
}

.row {
  margin-bottom: 0px !important;
}

.col {
  padding: 0 !important;
}

.flex {
  margin-left: -25px;
  display: flex;
  justify-content: space-between;
  align-items: stretch;
  flex-flow: row wrap;
}

.item-card {
  position: relative;
  flex: 1 0 300px;
  margin-bottom: 25px;
  margin-left: 25px;
  border-radius: 5px;
  overflow: hidden;

  &__img {
    width: 100%;
    height: 100%;
    overflow: hidden;

    img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }
  }
}

.flex-card-item {
  position: relative;
  flex: 1 0 300px;
  margin-bottom: 25px;
  margin-left: 25px;
}

.section {
  width: 100%;
  padding: 0px;
  position: relative;

  @media screen and (max-width: 600px) {
    & {
      text-align: center;
    }
  }

  &--seagreen {
    background: seagreen;
  }

  &--grey {
    background: #f2f2f2;
  }

  &--white {
    background: #fff;
  }

  &__content {
    padding: 100px 0px;

    &--small {
      padding: 50px 0px;
    }

    &__desc {
      &--size_m {
        font-size: 15px;
      }

      &--white {
        color: #fff;
      }

      &--black {
        color: #000;
      }
    }

    &__title {
      margin-bottom: 40px;

      &--large {
        font-size: 35px;
        line-height: 35px;
      }

      &--white {
        color: #fff;
      }

      &--black {
        color: #000;
      }
    }
  }

  &__info {
    padding-bottom: 100px;
    padding-top: 150px;

    @media screen and (max-width: 600px) {
      & {
        padding-top: 70px;
        padding-bottom: 50px;
      }
    }

    &__product {
      width: 600px;
      left: 50%;
      margin-left: -300px;
      position: relative;
      color: #fff;
      transition: 300ms;

      @media screen and (max-width: 600px) {
        & {
          width: 250px;
          left: 50%;
          margin-left: -125px;
          margin-bottom: 20px;
          color: #000;
        }
      }

      &__img {
        width: 250px;
        height: 175px;
        overflow: hidden;
        @include inline();

        img {
          width: 100%;
          height: 100%;
          object-fit: cover;
        }

        &--rounded {
          border-radius: 5px;
        }
      }

      @media screen and (max-width: 600px) {
        &__info {
          margin-top: 25px;
          width: 250px;
        }
      }

      &__info {
        @include inline();
        box-sizing: border-box;
        padding-left: 20px;

        &__desc {
          font-size: 12px;
          opacity: 0.6;
        }

        &__title {
          font-size: 35px;
          font-weight: bold;
          line-height: 45px;
          margin-top: 10px;
          margin-bottom: 20px;
        }
      }

      &:hover {
        background: rgba(0, 0, 0, 0.1);
      }
    }
  }
}

.header-flex {
  display: flex;
  justify-content: space-between;
  align-items: stretch;
  flex-flow: row nowrap;
}

.flex-header-item {
  flex: 1 0 1;
}

.header {
  padding: 15px 0px;
  position: fixed;
  width: 100%;
  min-height: 70px;
  z-index: 999;
  transition: 300ms;

  &--darken {
    background: rgba(0, 0, 0, 0.7);
  }

  &__logo {
    font-weight: bold;
    display: inline-block;
    padding: 10px 0px;
    color: #fff;
  }

  @media screen and (max-width: 992px) {
    &__logo {
      width: 200px;
      text-align: center;
      top: 15px;
      position: fixed;
      left: 50%;
      margin-left: -100px;
    }
  }

  &__avatar {
    width: 40px;
    height: 40px;
    overflow: hidden;
    border-radius: 50%;
    cursor: pointer;

    &:hover {
      opacity: 0.7;
      transition: 700ms;
    }

    img {
      width: 100%;
    }
  }

  &__menu {
    &__item {
      padding: 10px 25px;
      margin-left: 15px;
      display: inline-block;
      transition: 300ms;
      color: #fff;

      &--rounded {
        border-radius: 25px;
      }

      &:hover {
        background: rgba(0, 0, 0, 0.2);
        color: white;
      }
    }
  }
}

.button {
  padding: 7px 35px;
  text-align: center;
  color: #fff;
  display: inline-block;
  font-size: 12px;
  cursor: pointer;
  transition: 300ms;

  &:hover {
    opacity: 0.5;
  }

  &--white {
    background: #fff;
    color: #000;
  }

  &--bordered {
    border: 2px solid #fff;
  }

  &--rounded {
    border-radius: 20px;
  }

  @media screen and (max-width: 600px) {
    & {
      color: #000;
    }
    &--bordered {
      border: 2px solid #000;
    }
  }
}

.clearfix:after {
  content: " ";
  visibility: hidden;
  display: block;
  height: 0;
  clear: both;
}
</style>
