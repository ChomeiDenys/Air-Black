<script setup>
</script>

<template>
    <header>
    <a class="header-logo" href="#"
      ><svg width="45" height="26" viewBox="0 0 45 26" fill="white" xmlns="http://www.w3.org/2000/svg">
<path d="M7.128 17.964L13.428 4.356L19.728 17.964H7.128ZM21.24 21.204L23.292 25.632H26.856L15.12 0.431998H11.736L0 25.632H3.564L5.616 21.204H21.24Z" fill=""/>
<path d="M27.2025 2.448C27.2025 3.168 27.4185 3.744 27.8865 4.212C28.3545 4.68 28.9305 4.896 29.6505 4.896C30.3345 4.896 30.9105 4.68 31.3785 4.212C31.8465 3.744 32.0985 3.168 32.0985 2.448C32.0985 1.764 31.8465 1.188 31.3785 0.719999C30.9105 0.251999 30.3345 0 29.6505 0C28.9305 0 28.3545 0.251999 27.8865 0.719999C27.4185 1.188 27.2025 1.764 27.2025 2.448ZM31.1985 7.632H28.1025V25.632H31.1985V7.632Z" fill=""/>
<path d="M37.6183 10.332V7.632H34.6303V25.632H37.7263V17.244C37.7263 16.236 37.7983 15.336 37.9783 14.472C38.1223 13.644 38.4103 12.924 38.8423 12.312C39.2743 11.736 39.8143 11.268 40.4983 10.944C41.1463 10.62 42.0103 10.44 43.0183 10.44C43.3423 10.44 43.6303 10.476 43.9183 10.512C44.2063 10.548 44.4943 10.584 44.8183 10.656V7.38C44.5303 7.344 44.2423 7.308 43.9543 7.272C43.6663 7.236 43.3423 7.2 43.0543 7.2C41.7583 7.2 40.6783 7.488 39.7783 8.028C38.8783 8.568 38.1583 9.324 37.6183 10.332Z" fill=""/>
</svg>
</a>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#about">About us</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#work">Work</a></li>
          <li><a href="#contact-us">Contact Us</a></li>
        </ul>
        <ul>
          <li><a href="#hire-us">Hire us</a></li>
        </ul>
      </nav>
    </header>
</template> 

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
  background-color: #2C2C2C;
  padding: 0 227px;
}

ul {
  display: flex;
  column-gap: 60px;
  padding: 0;
}

li {
  list-style-type: none;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
  border-radius: 30px 0;
}

nav {
  width: 100%;
  text-align: center;
  margin-top: 2rem;
  display: flex;
  justify-content: space-between;
}

li a{
  font-weight: 700;
  font-size: 13px;
  line-height: 150%;
  letter-spacing: 3px;
  text-transform: uppercase;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

.header-logo{
  margin-right: 14px;
  margin-top: 13px;
}

.header-logo svg{
    transition: all 1s ease-out;

}

.header-logo svg:hover{
  fill: #144ed4;
  scale: 1.1;
}

header {
  display: flex;
  place-items: center;
  column-gap: 64px;
}

nav {
 margin-left: -1rem;
 font-size: 1rem;
 padding: 1rem 0;
 margin-top: 1rem;
}  

nav a:hover{
  color: #2060f6;
  /* text-decoration: underline;
  text-decoration-thickness: 2px;
  text-decoration-color: blue; */
}

</style>