<template>
  <div id="app">
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
    <main>
      <div id="main" class="page">
        <h1>Hi, this is Raymond</h1>
      </div>
      <div id="about" class="page">
        <h2>About me</h2>
        <p>I am a fullstack developer based in Hong Kong, with solid experience in Android development.</p>
        <p>I have been working @9GAG for several years, having hands on experiences with various developments and frameworks. Including API design, system architecture design and currently focusing on Android development.</p>
      </div>
      <div id="contacts" class="page">
        <h2>Contacts</h2>
        <ul>
          <li>
            <a href="https://www.facebook.com/dnomyar.tc" target="_blank">Facebook</a>
          </li>
          <li>
            <a href="https://twitter.com/am5a03" target="_blank">Twitter</a>
          </li>
          <li>
            <a href="https://github.com/am5a03" target="_blank">Github</a>
          </li>
          <li>
            <a href="https://www.linkedin.com/in/raymond-chan-7467ab31" target="_blank">LinkedIn</a>
          </li>
          <li>
            <a href="">Email</a>
          </li>
        </ul>
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
}

.page {
  height: 100vh;
}

nav {
  background-color: #333;
  overflow: hidden;
}

nav ul {
  margin: 0;
}

nav ul > li {
  float: left;
  display: block;
  padding: 16px 16px;
}

</style>
