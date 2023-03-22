<script setup></script>

<template>
  <div class="services" id="services">
    <div class="servis">
      <h6 class="servis-title">Proces</h6>
      <h3 class="servis-subtitle">
        Air is a full service <br />
        creative agency
      </h3>
      <p class="servis-text">
        Deep analytics, strong strategy and bright creative <br />
        ideas. <br />
        <br />
        We are sure that first-rate job is possible only if all <br />three
        components are united.
      </p>
    </div>
    <div class="cards">
      <div class="card-1">
        <div class="number">
          <p class="numb">001</p>
        </div>

        <p class="text">
          Brand Development <br />
          Copywriting <br />
          Logo & Webite Design <br />
          Packaging
        </p>

        <button class="learn-more">
          <div class="learn-more-arrow">
            <img src="/public/img/arrow.png" alt="arrow" />
          </div>
          <p class="learn-more-text">Learn more</p>
        </button>
      </div>
      <div class="card-2">
        <div class="number">
          <p class="numb">002</p>
        </div>

        <p class="text">
          Сontent Production <br />
          Graphic Design <br />
          Video Production <br />
          Post Production
        </p>

        <button class="learn-more">
          <div class="learn-more-arrow">
            <img src="/public/img/arrow.png" alt="arrow" />
          </div>
          <p class="learn-more-text">Learn more</p>
        </button>
      </div>
      <div class="card-3">
        <div class="number">
          <p class="numb">003</p>
        </div>

        <p class="text">
          Marketing Strategy <br> Email Marketing <br> Paid Advertising <br> Blog Content & SEO
        </p>

        <button class="learn-more">
          <div class="learn-more-arrow">
            <img src="/public/img/arrow.png" alt="arrow" />
          </div>
          <p class="learn-more-text">Learn more</p>
        </button>
      </div>
      <div class="card-4">
        <div class="number">
          <p class="numb">004</p>
        </div>

        <p class="text">
          Digital Communications <br> Influencer Marketing <br> Product Placements <br>
          Strategic Partnerships
        </p>

        <button class="learn-more">
          <div class="learn-more-arrow">
            <img src="/public/img/arrow.png" alt="arrow" />
          </div>
          <p class="learn-more-text">Learn more</p>
        </button>
      </div>
    </div>
  </div>

  <div class="background-approach">
    <section class="approach">
      <h6 class="approach-title">approach</h6>
      <h3 class="approach-subtitle">We strive to create meaningful projects</h3>

      <div class="approach-paragraphs">
        <div class="approach-brands">
          <img
            class="brands-icon"
            src="/public/img/brands-icon.png"
            alt="brands-icon"
          />

          <p class="brands-text">
            We are sure that the brands built on a strong strategy, big ideas
            and simple human values always win. Only such brands change the
            game.
          </p>
        </div>
        <div class="approach-media">
          <img
            class="media-icon"
            src="/public/img/media-icon.png"
            alt="media-icon"
          />

          <p class="media-text">
            No one can realize the idea as its creators. Therefore, we set up
            agency-based photo and video production departments.
          </p>
        </div>
        <div class="approach-prodjects">
          <img
            class="prodjects-icon"
            src="/public/img/prodjects-icon.png"
            alt="projects-icon"
          />

          <p class="prodjects-text">
            We strive to create meaningful projects that make brands valuable,
            and the world around us more aesthetic.
          </p>
        </div>
      </div>
    </section>

    <img
      src="/public/img/approach-img.png"
      class="approach-img"
      alt="approach-img"
    />
  </div>

  <div class="testimonials" id="work">
    <h6 class="testimonials-title">Testimonials</h6>
    <h3 class="testimonials-subtitle">
      What <br />
      people say
    </h3>
  </div>

  <div class="team">
    <div class="team-card">
      <div class="team-card-logo">
        <div class="team-card-rectangle-left"></div>
        <img
          class="team-card-photo"
          src="/public/img/team-card-photo-1.png"
          alt="team-card-photo-1"
        />
        <div class="team-card-rectangle-right"></div>
      </div>
      <img
        class="team-card-item"
        src="/public/img/team-card-item.svg"
        alt="team-card-item"
      />
      <p class="team-card-text">
        AIR’s ideas are refreshing and out of <br />
        the box. Authentic team that focuses <br />
        on the important path of the brand.
      </p>
      <p class="team-card-title">Tal Gilad</p>
      <h6 class="team-card-subtitle">Teach for America</h6>
    </div>
    <div class="team-card">
      <div class="team-card-logo">
        <div class="team-card-rectangle-left"></div>
        <img
          class="team-card-photo"
          src="/public/img/team-card-photo-2.png"
          alt="team-card-photo-2"
        />
        <div class="team-card-rectangle-right"></div>
      </div>
      <img
        class="team-card-item"
        src="/public/img/team-card-item.svg"
        alt="team-card-item"
      />
      <p class="team-card-text">
        AIR is an exceptional agency that leads <br />
        with creative talent, first-class account <br />
        servicing.
      </p>
      <p class="team-card-title">Azadeh Hawkins</p>
      <h6 class="team-card-subtitle">Hawkins Consulting</h6>
    </div>
    <div class="team-card">
      <div class="team-card-logo">
        <div class="team-card-rectangle-left"></div>
        <img
          class="team-card-photo"
          src="/public/img/team-card-photo-3.png"
          alt="team-card-photo-3"
        />
        <div class="team-card-rectangle-right"></div>
      </div>
      <img
        class="team-card-item"
        src="/public/img/team-card-item.svg"
        alt="team-card-item"
      />
      <p class="team-card-text">
        AIR raises the agency bar to <br />
        stratospheric heights on both creative <br />
        output and client service.
      </p>
      <p class="team-card-title">Michel Grover</p>
      <h6 class="team-card-subtitle">Hulu</h6>
    </div>
  </div>
</template>

<style scoped>
.services {
  width: 100%;
  display: flex;
  padding: 170px 227px 0 227px;
  justify-content: space-between;
}

.servis {
  margin-top: 130px;
}

.servis-title {
  font-weight: 700;
  font-size: 13px;
  line-height: 20px;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #c0cdd7;
  margin-bottom: 16px;
}

.servis-subtitle {
  font-weight: 600;
  font-size: 32px;
  line-height: 130%;
  display: flex;
  color: #253757;
  margin-bottom: 24px;
}

.servis-text {
  font-weight: 400;
  font-size: 14px;
  line-height: 150%;
  color: #6c788b;
}

.cards {
  z-index: 1;
}

.card-1,
.card-2,
.card-3,
.card-4 {
  height: 264px;
  width: 264px;
  background-color: #ffffff;
  border-radius: 16px;
  padding-left: 30px;
  padding-top: 30px;
  display: grid;
}

.number {
  width: 46px;
  height: 24px;
  background-color: #e5e5e5;
  border-radius: 23px;
}

.numb {
  color: #2060f6;
  text-align: center;
}

.text {
  font-weight: 600;
  font-size: 13px;
  line-height: 150%;
  color: #6c788b;
}

.learn-more {
  display: flex;
  margin-bottom: 14px;
}
.learn-more-arrow {
  background-color: #2060f6;
  border-radius: 45px;
  width: 40px;
  height: 40px;
  padding: 8px;
}

.learn-more-text {
  margin-top: 7px;
  margin-left: 20px;
  color: #334563;
}

.cards {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(5, 1fr);
  grid-column-gap: 30px;
  grid-row-gap: 30px;
}

.card-1 {
  grid-area: 2 / 1 / 4 / 2;
}
.card-2 {
  grid-area: 1 / 2 / 3 / 3;
}
.card-3 {
  grid-area: 4 / 1 / 6 / 2;
}
.card-4 {
  grid-area: 3 / 2 / 5 / 3;
}

.background-approach {
  background-color: #2c2c2c;
  border-radius: 30px 0 0 30px;
  margin-left: 61px;
  display: flex;
  margin-top: -65px;
}

.approach {
  padding: 204px;
}

.approach-title {
  font-weight: 700;
  font-size: 13px;
  line-height: 20px;
  letter-spacing: 3px;
  text-transform: uppercase;
}

.approach-subtitle {
  font-weight: 600;
  font-size: 32px;
  line-height: 150%;
}

.approach-paragraphs {
  display: flex;
  justify-content: space-around;
  flex-direction: column;
}

.approach-brands,
.approach-media,
.approach-prodjects {
  width: 363px;
  font-style: normal;
  font-weight: 400;
  font-size: 15px;
  display: flex;
  column-gap: 30px;
  align-items: center;
}

.approach-brands {
  padding-top: 40px;
}

.approach-media,
.approach-prodjects {
  margin-top: 70px;
}

.brands-icon,
.media-icon,
.prodjects-icon {
  width: 64px;
  height: 64px;
  background-color: #ffffff;
  border-radius: 45px;
  padding: 21px;
}

.approach-img {
  width: 687px;
  height: 680px;
  margin-top: 331px;
  border-radius: 30px 0 0 0;
}

.testimonials {
  padding: 134px 0 85px 215px;
}

.testimonials-title {
  font-weight: 700;
  font-size: 13px;
  line-height: 20px;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #c0cdd7;
  margin-bottom: 15px;
}

.testimonials-subtitle {
  font-weight: 600;
  font-size: 32px;
  line-height: 150%;
  color: #253757;
}

.team {
  display: flex;
  justify-content: space-between;
  margin: 0 215px;
}

.team-card {
  width: 314px;
  align-items: center;
  background-color: #ffffff;
  border-radius: 16px;
  display: flex;
  justify-content: center;
  flex-direction: column;
  margin-bottom: 168px;
}

.team-card-logo {
  width: 250px;
  position: relative;
  background-color: #ffffff;
  display: flex;
  justify-content: space-around;
  margin: 32px 32px 24px 32px;
}

.team-card-rectangle-left {
  width: 56px;
  height: 139px;
  background-color: #2060f6;
  border-radius: 12px;
  transform: rotate(25deg);
  position: absolute;
  left: 47px;
  top: 12px;
}

.team-card-rectangle-right {
  width: 56px;
  height: 139px;
  background-color: #2060f6;
  border-radius: 12px;
  transform: rotate(25deg);
  position: absolute;
  top: 40%;
  right: 19%;
}

.team-card-photo {
  z-index: 1;
  border-radius: 70px;
  width: 140px;
  height: 140px;
  display: block;
  margin: 55px;
}

.team-card-item {
  margin-bottom: 8px;
}

.team-card-text {
  font-weight: 600;
  font-size: 13px;
  line-height: 150%;
  text-align: center;
  color: #6c788b;
}

.team-card-title {
  font-size: 13px;
  line-height: 150%;
  color: #253757;
  margin: 16px 0 4px 0;
  font-weight: 600;
}

.team-card-subtitle {
  font-weight: 700;
  font-size: 13px;
  line-height: 20px;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #c0cdd7;
  margin-bottom: 32px;
}

button {
  border: unset;
  background-color: #ffffff;
  cursor: pointer;
}
</style>
