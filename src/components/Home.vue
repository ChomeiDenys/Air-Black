<script setup>
import SliderHome from '../components/SliderHome.vue'

</script>

<template>
  <section id="home">

    <div class="home">
      <div class="home__text">
        <h1 class="home__title">Strategic Agency</h1>
        <p class="home__subtitle">We believe in the power of bold ideas that can solve business challenges.</p>
        <button><p class="button-text">Learn more</p></button>
      </div>

      <SliderHome></SliderHome>
    </div>


    <div class="home__about">
      <div style="width: 800px;">
<h2 class="home__about-title">Who we are</h2>
<p class="home__about-subtitle">We embrace a strategic approach to creative ideas. We are interested in people and human
  relationships. This is the main
  thing you need to know about us. We believe in the power of bold ideas that can solve business challenges.</p>
      </div>
     
    </div>


  </section>
</template> 
<style scoped>
.home__about {
  margin-top: 148px;
    margin-bottom: 148px;
 
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.home__about-title {font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 32px;
  line-height: 150%;

  display: flex;
  align-items: center;


  color: #253757;}

.home__about-subtitle {font-family: 'Open Sans';
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 150%;


  color: #6C788B;}


#home{
 background-color:  #E5E5E5;
}
.home {
  display: flex;
  justify-content: space-between;
  background-color: #2C2C2C;
  padding: 28px 0 0 227px;
  border-radius: 0 0 30px 30px;
}

.home__text {
  display: flex;
  flex-direction: column;
  width: 362px;
}

.home__title {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 64px;
  line-height: 68px;

  letter-spacing: -2px;

  color: #FFFFFF;
  margin-top: 100px;
}

.home__subtitle {
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 150%;


  color: #FFFFFF;
  margin-top: 32px;
}

button {
  width: 226px;
  height: 50px;
  background: #2060F6;
  border-radius: 8px;
  margin-top: 83px;
  border: unset;
  cursor: pointer;
  transition: all 0.8s ease-out;
}

button:hover {
 scale: 1.1; 
}

.button-text{
font-family: 'Poppins';
font-weight: 600;
font-size: 15px;
line-height: 22px;
color: #FFFFFF;
}
</style>