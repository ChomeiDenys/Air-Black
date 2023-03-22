

<template>
<swiper :navigation="true" :modules="modules"     :loop="true"
 class="mySwiper">
  <swiper-slide>
    <div class="carousel__item">
      <img class="carousel__img" src="/public/img/slider-1.png" />
      <div class="carousel__title">
        <h3 class="">Intro</h3>
        <p>By the same illusion which lifts the horizon</p>
      </div>
  </div>
</swiper-slide>
  <swiper-slide>
    <div class="carousel__item">
      <img class="carousel__img" src="/public/img/slider-2.png" />
      <div class="carousel__title">
        <h3 class="">Intro</h3>
        <p>By the same illusion which lifts the horizon</p>
      </div>
    </div>
  </swiper-slide>
    <swiper-slide>
      <div class="carousel__item">
        <img class="carousel__img" src="/public/img/slider-3.png" />
        <div class="carousel__title">
          <h3 class="">Intro</h3>
          <p>By the same illusion which lifts the horizon</p>
        </div>
      </div>
    </swiper-slide>
</swiper>

</template>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';

import 'swiper/css/navigation';

// import required modules
import { Navigation } from 'swiper';

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Navigation],
    };
  },
};

</script>
<style scoped>
h3{
  right: 33%;
 
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 9px;
    line-height: 20px;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: #FFFFFF;
}

p{
    right: 33%;
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 9px;
    width: 55%;
    line-height: 140%;
    color: #FFFFFF;
}
.carousel {
  max-width: 50%;
}

.carousel__title {
  text-align: start;
  position: absolute;
  bottom: 50px;
  left: 30%;
  width: 264px;
}

.swiper {
  width: 50%;
  height: 100%;
  margin: 0;
  border-radius: 30px 0;
}

.swiper-slide {
  text-align: center;
  font-size: 18px;
  background: #fff;

  display: flex;
  justify-content: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

:deep(.swiper-button-prev){
left: 5%;
}

:deep(.swiper-button-next) {
  right: 86%;
  
}

:deep(.swiper-button-prev),
:deep(.swiper-button-next) {
  color: #253757;
  background-color: #FFFFFF;
  border-radius: 50px;
  width: 15px;
  height: 15px;
  padding: 11px;
  top: 90%;
  
}

:deep(.swiper-button-next):after,
:deep(.swiper-button-prev):after{
    font-size: 9px !important;
}
</style>



