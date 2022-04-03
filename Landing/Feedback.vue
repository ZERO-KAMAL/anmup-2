<template>
  <div id="feedback" class="section__padding">
    <div class="section__title">
      <h2>People’s Feedback</h2>
      <p>What our clients and locals says about us</p>
    </div>

    <div class="container">
      <div class="row">
        <swiper
          :space-between="50"
          @swiper="onSwiper"
          @slideChange="onSlideChange"
          :pagination="{
            clickable: true,
          }"
          :modules="modules"
          :loop="true"
          :breakpoints="{
            '640': {
              slidesPerView: 1,
              spaceBetween: 20,
            },
            '768': {
              slidesPerView: 2,
              spaceBetween: 40,
            },
            '1024': {
              slidesPerView: 3,
              spaceBetween: 50,
            },
          }"
          :autoplay="{
            delay: 2500,
            disableOnInteraction: false,
          }"
        >
          <swiper-slide>
            <div class="feedback__box">
              <div class="feedback__box-img">
                <img src="../assets/images/feedback/feedback1.svg" alt="" />
                <img
                  src="../assets/images/feedback/client1.svg"
                  alt=""
                  class="client-img"
                />
              </div>
              <div
                class="
                  feedback__box-content
                  d-flex
                  align-items-center
                  justify-content-center
                  flex-column
                "
              >
                <h4>Cody Fisher</h4>
                <span>Surkhet Local</span>
                <p>
                  Lorem ipsum dolor sit amet, consecte tur adipiscing elit.
                  Ultrices blandit pelle ntesque nibh arcu elementum odio justo.
                  Rhoncus.
                </p>
              </div>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div class="feedback__box">
              <div class="feedback__box-img">
                <img src="../assets/images/feedback/feedback2.svg" alt="" />
                <img
                  src="../assets/images/feedback/client2.svg"
                  alt=""
                  class="client-img"
                />
              </div>
              <div
                class="
                  feedback__box-content
                  d-flex
                  align-items-center
                  justify-content-center
                  flex-column
                "
              >
                <h4>Bessie Cooper</h4>
                <span>Surkhet Mayor</span>
                <p>
                  Lorem ipsum dolor sit amet, consecte tur adipiscing elit.
                  Ultrices blandit pelle ntesque nibh arcu elementum odio justo.
                  Rhoncus.
                </p>
              </div>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div class="feedback__box">
              <div class="feedback__box-img">
                <img src="../assets/images/feedback/feedback2.svg" alt="" />
                <img
                  src="../assets/images/feedback/client3.svg"
                  alt=""
                  class="client-img"
                />
              </div>
              <div
                class="
                  feedback__box-content
                  d-flex
                  align-items-center
                  justify-content-center
                  flex-column
                "
              >
                <h4>Arlene McCoy</h4>
                <span>Hospital CEO</span>
                <p>
                  Lorem ipsum dolor sit amet, consecte tur adipiscing elit.
                  Ultrices blandit pelle ntesque nibh arcu elementum odio justo.
                  Rhoncus.
                </p>
              </div>
            </div>
          </swiper-slide>
        </swiper>
      </div>
    </div>
  </div>
</template>

<script>
import { Navigation, Pagination } from "swiper";

import { SwiperCore, Swiper, SwiperSlide } from "swiper-vue2";
// Import Swiper styles
import "swiper/swiper-bundle.css";

SwiperCore.use([Navigation, Pagination]);
export default {
  name: "feedback",
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Pagination],
    };
  },
};
</script>
