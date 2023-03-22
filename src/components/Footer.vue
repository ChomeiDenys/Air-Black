<script setup></script>

<template>
  <div class="components-banner">
    <div class="components">
      <h2 class="components-title">Vision, Passion, Results</h2>
      <p class="components-text">
        We are sure that first-rate job is possible only if all three <br />
        components are united.
      </p>
      <button>
        <p class="button-text">Apply</p>
      </button>
    </div>

    <div class="shape shape-1"></div>
    <div class="shape shape-2"></div>
    <div class="shape shape-3"></div>
    <div class="shape shape-4"></div>
    <div class="shape shape-5"></div>
    <div class="shape shape-6"></div>
    <div class="shape shape-7"></div>
    <div class="shape shape-8"></div>
    <div class="shape shape-9"></div>
    <div class="shape shape-10"></div>
    <div class="shape shape-11"></div>
    <div class="shape shape-12"></div>
  </div>

  <div class="contacts-background">
    <div class="contacts">
      <div class="contact-form" id="hire-us">
        <h3 class="contact-form-title">Send us a message</h3>
        <div class="form">
          <input type="email" class="email" placeholder="Email" />
          <input type="text" class="name" placeholder="Your name" />
          <input type="text" class="text" placeholder="Your message" />
        </div>
        <button><p class="button-text">Send</p></button>
      </div>

      <div class="contact-us" id="contact-us">
        <h3 class="contact-us-title">Contact us</h3>
        <div class="contact-us-form">
          <div class="call_block">
            <h6 class="call-title">Call us</h6>
            <p class="call-text">654 321 987</p>
          </div>
          <div class="visit_block">
            <h6 class="visit-title">Visit us</h6>
            <p class="visit-text">2905 West Drive, Buffalo Grove</p>
          </div>
          <div class="socials_block">
            <h6 class="socials-title">our socials</h6>
            <div class="socials-logo">
              <a href="https://www.facebook.com/facebook/?locale=uk_UA" target="_blank"><img src="/public/img/facebook.svg" alt="facebook-logo"></a>
              <a href="https://twitter.com/?lang=uk" target="_blank"><img src="/public/img/twitter.svg" alt="tvitter-logo"></a>
              <a href="https://www.instagram.com/" target="_blank"><img src="/public/img/instagram.svg" alt="instagram-logo"></a>
            </div>
          </div>
          
        </div>
      </div>
    </div>
  </div>

  <footer>
    <a class="footer-logo" href="#"
      ><svg width="45" height="26" viewBox="0 0 45 26" fill="white" xmlns="http://www.w3.org/2000/svg">
<path d="M7.128 17.964L13.428 4.356L19.728 17.964H7.128ZM21.24 21.204L23.292 25.632H26.856L15.12 0.431998H11.736L0 25.632H3.564L5.616 21.204H21.24Z" fill=""/>
<path d="M27.2025 2.448C27.2025 3.168 27.4185 3.744 27.8865 4.212C28.3545 4.68 28.9305 4.896 29.6505 4.896C30.3345 4.896 30.9105 4.68 31.3785 4.212C31.8465 3.744 32.0985 3.168 32.0985 2.448C32.0985 1.764 31.8465 1.188 31.3785 0.719999C30.9105 0.251999 30.3345 0 29.6505 0C28.9305 0 28.3545 0.251999 27.8865 0.719999C27.4185 1.188 27.2025 1.764 27.2025 2.448ZM31.1985 7.632H28.1025V25.632H31.1985V7.632Z" fill=""/>
<path d="M37.6183 10.332V7.632H34.6303V25.632H37.7263V17.244C37.7263 16.236 37.7983 15.336 37.9783 14.472C38.1223 13.644 38.4103 12.924 38.8423 12.312C39.2743 11.736 39.8143 11.268 40.4983 10.944C41.1463 10.62 42.0103 10.44 43.0183 10.44C43.3423 10.44 43.6303 10.476 43.9183 10.512C44.2063 10.548 44.4943 10.584 44.8183 10.656V7.38C44.5303 7.344 44.2423 7.308 43.9543 7.272C43.6663 7.236 43.3423 7.2 43.0543 7.2C41.7583 7.2 40.6783 7.488 39.7783 8.028C38.8783 8.568 38.1583 9.324 37.6183 10.332Z" fill=""/>
</svg>
</a>
    <nav class="nav-footer">
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#about">About us</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#work">Work</a></li>
        <li><a href="#contact-us">Contact Us</a></li>
      </ul>
    </nav>
  </footer>
</template>

<style scoped>
.components-banner {
  height: 700px;
  background-color: #ffffff;
  display: flex;
  justify-content: center;
  position: relative;
}

.components {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.components-title {
  font-weight: 600;
  font-size: 52px;
  line-height: 150%;
  color: #253757;
}

.components-text {
  font-weight: 600;
  font-size: 24px;
  line-height: 150%;
  text-align: center;
  color: #6c788b;
  margin: 24px 0 64px 0;
}

button {
  width: 226px;
  height: 56px;
  background: #2060f6;
  border-radius: 8px;
  border: unset;
  cursor: pointer;
  transition: all 0.8s ease-out;
}

button:hover {
 scale: 1.1; 
}

.button-text {
  font-family: "Poppins";
  font-weight: 600;
  font-size: 15px;
  color: #ffffff;
}

.shape {
  position: absolute;
}

.shape-1 {
  width: 85.61px;
  height: 33.84px;
  left: 213px;
  top: 92px;
  opacity: 0.5;
  border: 3px solid #2060f6;
  border-radius: 12px;
  transform: rotate(-65.1deg);
}

.shape-2 {
  position: absolute;
  width: 45.28px;
  height: 17.9px;
  left: 423px;
  top: 77px;
  opacity: 0.5;
  border: 3px solid #2060f6;
  border-radius: 6px;
  transform: rotate(-65.1deg);
}

.shape-3 {
  position: absolute;
  width: 143.04px;
  height: 56.54px;
  left: 245px;
  top: 327px;
  opacity: 0.5;
  border: 5px solid #2060f6;
  border-radius: 12px;
  transform: rotate(-65.1deg);
}

.shape-4 {
  position: absolute;
  width: 67.36px;
  height: 26.63px;
  left: 82.16px;
  top: 370.12px;
  opacity: 0.5;
  border: 5px solid #2060f6;
  border-radius: 12px;
  transform: rotate(-65.1deg);
}

.shape-5 {
  position: absolute;
  width: 93.54px;
  height: 36.98px;
  left: 131.42px;
  top: 518.45px;
  opacity: 0.5;
  border: 5px solid #2060f6;
  border-radius: 12px;
  transform: rotate(-65.1deg);
}

.shape-6 {
  position: absolute;
  width: 45.28px;
  height: 17.9px;
  right: 1038.7px;
  top: 478px;
  opacity: 0.5;
  border: 3px solid #2060f6;
  border-radius: 6px;
  transform: rotate(-65.1deg);
}

.shape-7 {
  position: absolute;
  width: 45.28px;
  height: 17.9px;
  right: 508.27px;
  top: 516px;
  opacity: 0.5;
  border: 3px solid #2060f6;
  border-radius: 6px;
  transform: rotate(-65.1deg);
}

.shape-8 {
  position: absolute;
  width: 143.04px;
  height: 56.54px;
  right: 215.58px;
  top: 130.96px;

  opacity: 0.5;
  border: 5px solid #2060f6;
  border-radius: 12px;
  transform: rotate(-65.1deg);
}

.shape-9 {
  position: absolute;
  width: 53.69px;
  height: 21.22px;
  right: 111.13px;
  top: 109.48px;
  opacity: 0.5;
  border: 3px solid #2060f6;
  border-radius: 8px;
  transform: rotate(-65.1deg);
}

.shape-10 {
  position: absolute;
  width: 86.41px;
  height: 34.16px;
  right: 67.04px;
  top: 276.5px;
  opacity: 0.5;
  border: 3px solid #2060f6;
  border-radius: 12px;
  transform: rotate(-65.1deg);
}

.shape-11 {
  position: absolute;
  width: 85.61px;
  height: 33.84px;
  right: 314.27px;
  top: 385.16px;
  opacity: 0.5;
  border: 3px solid #2060f6;
  border-radius: 12px;
  transform: rotate(-65.1deg);
}

.shape-12 {
  position: absolute;
  width: 153.61px;
  height: 60.72px;
  right: 143.56px;
  top: 413.16px;
  opacity: 0.5;
  border: 5px solid #2060f6;
  border-radius: 12px;
  transform: rotate(-65.1deg);
}

.contacts-background {
  background-color: #ffffff;
}

.contacts {
  background: #2c2c2c;
  border-radius: 30px 30px 0 0;
  display: flex;
  justify-content: space-around;
}

.contact-form {
  padding: 180px 0 104px 227px;
}

.contact-form-title {
  font-weight: 600;
  font-size: 32px;
  line-height: 150%;
}

.form {
  display: flex;
  flex-direction: column;
  row-gap: 48px;
  margin: 56px 0 80px 0;
}

.email {
  background: #2c2c2c;
  border: unset;
  border-bottom: 1px solid white;
  padding: 15px 241px 15px 0;
  color: #ffffff;
  font-family: "Poppins";
  font-weight: 600;
  font-size: 15px;
  line-height: 22px;
  opacity: 0.7;
}

.email:focus-visible {
  border-bottom: 1px solid #144ed4;
  outline: unset;
}

/* .email::placeholder{
  font-family: 'Poppins';
  font-weight: 600;
  font-size: 15px;
  line-height: 22px;
} */

.name {
  background: #2c2c2c;
  border: unset;
  border-bottom: 1px solid white;
  padding: 0 241px 15px 0;
  font-family: "Poppins";
  font-weight: 600;
  font-size: 15px;
  line-height: 22px;
  color: #ffffff;
  opacity: 0.7;
}

.name:focus-visible {
  border-bottom: 1px solid #144ed4;
  outline: unset;
}

.text {
  background: #2c2c2c;
  border: unset;
  border-bottom: 1px solid white;
  padding: 0 241px 15px 0;
  font-family: "Poppins";
  font-weight: 600;
  font-size: 15px;
  line-height: 22px;
  color: #ffffff;
  opacity: 0.7;
}

.text:focus-visible {
  border-bottom: 1px solid #144ed4;
  outline: unset;
}

.contact-us {
  margin: 180px 325px 164px 0;
}

.contact-us-title {
  font-weight: 600;
  font-size: 32px;
  line-height: 150%;
  margin-bottom: 56px;
}

.contact-us-form{
  display: flex;
  flex-direction: column;
  row-gap: 48px;
}

.call-title, .visit-title
 {
  margin-bottom: 8px;
}

.call-title, .visit-title, .socials-title{
font-weight: 700;
font-size: 13px;
line-height: 20px;
letter-spacing: 3px;
text-transform: uppercase;
opacity: 0.5;
}

.socials-logo{
  display: flex;
  column-gap: 32px;
}

.socials-logo * {
  width: 32px;
  height: 32px;
}

.socials-title{
  margin-bottom: 16px;
}

.call-text, .visit-text{
  font-weight: 600;
  font-size: 24px;
  line-height: 150%;
}

footer {
  line-height: 1.5;
  background-color: #2c2c2c;
  padding: 0 266px;
  display: flex;
  align-items: center;
}

ul {
  display: flex;
  column-gap: 64px;
}

li {
  list-style-type: none;
}

.footer-logo svg{
    transition: all 1s ease-out;

}

.footer-logo svg:hover{
  fill: #144ed4;
  scale: 1.1;
}

.nav-footer a:hover{
  color: #2060f6;
  
}

nav {
  width: 100%;
  text-align: center;
  margin-top: 2rem;
  display: flex;
  justify-content: end;
  margin-bottom: 45px;
}

li a{
  font-weight: 700;
  font-size: 13px;
  line-height: 150%;
  letter-spacing: 3px;
  text-transform: uppercase;
}
</style>
