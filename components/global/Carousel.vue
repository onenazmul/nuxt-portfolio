<template>
  <div class="carousel-wrapper">
    <div
      class="swiper"
      v-swiper:myDirectiveSwiper="swiperOptions"
      @ready="onSwiperRedied"
      @click-slide="onSwiperClickSlide"
      @slide-change-transition-start="onSwiperSlideChangeTransitionStart"
    >
      <div class="swiper-wrapper">
        <div class="swiper-slide" v-for="index in 10" :key="index">
          <div class="slide-inner">
            <!-- <span>Slide {{ index }}</span> -->
            <img
              src="https://www.portotheme.com/wordpress/porto/wp-content/uploads/images/logo-4.png"
              alt=""
            />
          </div>
        </div>
      </div>
      <div class="swiper-pagination swiper-pagination-bullets"></div>
      <!-- <div class="swiper-button-prev" slot="button-prev"></div>
      <div class="swiper-button-next" slot="button-next"></div> -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'carousel',
  data() {
    return {
      swiperOptions: {
        loop: true,
        centeredSlides: true,
        grabCursor: true,
        mousewheel: true,
        pagination: {
          el: '.swiper-pagination',
          //dynamicBullets: true
          clickable: true
        },
        keyboard: {
          enabled: true
        },
        autoplay: {
          delay: 2500,
          disableOnInteraction: false
        },
        // navigation: {
        //   nextEl: '.swiper-button-next',
        //   prevEl: '.swiper-button-prev'
        // },
        breakpoints: {
          1024: {
            slidesPerView: 7,
            spaceBetween: 30
          },
          768: {
            slidesPerView: 2,
            spaceBetween: 30
          },
          640: {
            slidesPerView: 2,
            spaceBetween: 20
          },
          320: {
            slidesPerView: 1,
            spaceBetween: 10
          }
        }
      }
    }
  },
  methods: {
    onSwiperRedied(swiper) {
      console.log('Swiper redied!', swiper)
    },
    onSwiperSlideChangeTransitionStart() {
      console.log('SwiperSlideChangeTransitionStart!')
    },
    onSwiperClickSlide(index, reallyIndex) {
      console.log('Swiper click slide!', reallyIndex)
    }
  }
}
</script>

<style lang="scss" scoped>
.carousel-wrapper {
  height: auto;
  .swiper {
    height: auto;
    width: 100%;
    .swiper-wrapper {
      padding: 28px 0 50px;
      .swiper-slide {
        text-align: center;
        display: flex;
        justify-content: center;
        align-items: center;
        .slide-inner {
          max-width: 170px;
        }
      }
    }
  }
}
</style>
