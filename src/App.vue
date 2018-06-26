<template>
  <div id="app">
    <main>
      <div id="mainWrapper">
        <div id="main" class="page">
          <nav id="nav">
            <ul class="nav-default">
              <li>
                <a href="#home">Home</a>
              </li>
              <li>
                <a href="#about">About me</a>
              </li>
              <li>
                <a href="#contacts">Contacts</a>
              </li>
            </ul>
          </nav>
          <div id="headline">
            <h1>Hi, this is Raymond</h1>
            <h2>A fullstack developer based in Hong Kong</h2>
          </div>
        </div>
      </div>
      <div id="about" class="page">
        <h2>About me</h2>
        <p class="description">
          I am a fullstack developer based in Hong Kong, with solid experience in Android development. I have been working <a href="https://9gag.com/u/ctc2">@9GAG</a> for several years, having hands on experiences with various developments and frameworks. Including API design, system architecture design and currently focusing on Android development.
          These are the things that I have solid experience:
        </p>
        <div class="skillset">
          <i class="ico fab fa-android fa-8x"></i>
          <i class="ico fab fa-java fa-8x"></i>
        </div>
        <p class="description">
          These are other skillsets that I know
        </p>
        <div class="skillset">
          <i class="ico fab fa-laravel fa-3x"></i>
          <i class="ico fab fa-react fa-3x"></i>
          <i class="ico fab fa-js-square fa-3x"></i>
        </div>
        <p class="description">
          In my spare time, I like reading, playing computer games (Hearthstone, Overwatch, Northgard or whatever interesting) and wandering around and shooting some random photos.
        </p>
      </div>
      <div id="contacts" class="page">
        <h2>Contacts</h2>
        <p class="description">Feel free to contact me!</p>
        <div id="contactMethods">
          <a href="https://www.facebook.com/dnomyar.tc" target="_blank">
            <i class="ico fab fa-facebook-square fa-5x"></i>
          </a>
          <a href="https://twitter.com/am5a03" target="_blank">
            <i class="ico fab fa-twitter-square fa-5x"></i>
          </a>
          <a href="https://medium.com/@raymondctc" target="_blank">
            <i class="ico fab fa-medium fa-5x"></i>
          </a>
          <a href="https://github.com/am5a03" target="_blank">
            <i class="ico fab fa-github-square fa-5x"></i>
          </a>
          <a href="https://www.linkedin.com/in/raymond-chan-7467ab31" target="_blank">
            <i class="ico fab fa-linkedin fa-5x"></i>
          </a>
          <a href="mailto:am5a03@gmail.com">
            <i class="ico fas fa-envelope-square fa-5x"></i>
          </a>
        </div>

      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
/* #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */

/* h1 {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  font-size: 10em;
  margin: 0;
  padding: 0;
} */

body {
  margin: 0 auto;
  font-family: 'Questrial', sans-serif;
  font-size: 16px;
  background: #f6f6f6;
}

h1, h2, h3, h4, h5, h6 {
  color: #111
}

.page {
  height: 100vh;
  padding: 0 1.5em 0 1.5em;
  margin: 0 auto;
  max-width: 50em;
  overflow-y: auto;
}

.divider {
  border: 1px solid #fff;
}

nav {
  margin-left: -1.5em;
  margin-right: -1.5em;
  overflow: hidden;
}

nav ul > li {
  float: left;
  display: block;
  padding: 1.5em 1.5em;
}

li a {
  color: #fff;
}

ul {
  margin: 0;
  padding: 0;
}

p {
  line-height: 2;
}

p.description {
  /* max-width: 75%; */
  text-align: justify;
  color: #666;
}

@media screen and (max-width: 600px) {
  p.description {
    max-width: 100%;
    text-align: justify;
    color: #666;
  }  
}

#mainWrapper {
  background: url('./images/bg1.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

#main h1 {
  color: #fff;
}

#main h2 {
  color: #ddd;
}

#headline {
  position: absolute;
  top: 40%;
}

.skillset {
  text-align: center;
}

#contactMethods {
  text-align: center;
}

.ico {
  color: #666;
}

#contactMethods > a {
  padding: 1em;
}

</style>
