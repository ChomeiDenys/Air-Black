<script setup></script>

<template>
  <section class="about" id="about">
    <h2 class="about-title">Our expertise</h2>
    <div class="about-wrapper">
      <div class="about-item">
        <img
          class="about-item-image"
          src="/public/img/item-img-1.png"
          alt="item-img-1"
        />
        <h4 class="about-item-title">Branding</h4>
        <p class="about-item-suptitle">
          We create additional value for companies, products, services as well
          as verbal and visual ways to deliver it to the audience.
        </p>
      </div>
      <div class="about-item">
        <img
          class="about-item-image"
          src="/public/img/item-img-2.png"
          alt="item-img-2"
        />
        <h4 class="about-item-title">Communication</h4>
        <p class="about-item-suptitle">
          We strive to create communications that can increase media
          performance. We use everything — words, meanings, stories, art,
          movies.
        </p>
      </div>
      <div class="about-item">
        <img
          class="about-item-image"
          src="/public/img/item-img-3.png"
          alt="item-img-3"
        />
        <h4 class="about-item-title">Strategy</h4>
        <p class="about-item-suptitle">
          We create business growth strategies, from the moment of its birth to
          the achievement of the necessary business indicators.
        </p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.about {
  background-color: #ffffff;
}

.about-title {
  color: #253757;
  font-family: "Poppins";
  font-style: normal;
  font-weight: 600;
  font-size: 52px;
  padding-top: 128px;
  padding-bottom: 128px;
  text-align: center;
}

.about-wrapper {
  display: flex;
  justify-content: space-between;
  padding: 0 227px 180px 227px;
}

.about-item {
  max-width: 260px;
  text-align: center;
}

.about-item-image {
  border-radius: 16px;
  width:166px ;
}

.about-item-title {
  color: #253757;
  font-family: "Poppins";
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
}

.about-item-suptitle {
  color: #6c788b;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
}
</style>
