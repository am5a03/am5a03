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
          I'm a fullstack developer based in Hong Kong, with a proven track record of learning whatever's thrown at me—often with zero prior knowledge and living to tell the tale. Currently working <a href="https://9gag.com/u/ctc2">@9GAG</a> since 2014, where I've worn more hats than a millinery shop: backend engineer, Android developer, Flutter experimentalist, and most recently, web3/AI R&D engineer. If there's a framework or technology I haven't learned on the job, it's probably because it doesn't exist yet.
        </p>

        <h3 class="section-title">Education</h3>
        <div class="timeline-item">
          <div class="timeline-year">2024</div>
          <div class="timeline-content">
            <strong>Diploma in Management</strong> — Douglas College<br>
            <span class="timeline-note">Because one can't just code forever... or can they?</span>
          </div>
        </div>
        <div class="timeline-item">
          <div class="timeline-year">2012</div>
          <div class="timeline-content">
            <strong>Bachelor of Business Administration (Information Systems)</strong> — Hong Kong University<br>
            <span class="timeline-note">Where the journey into the digital realm began</span>
          </div>
        </div>

        <h3 class="section-title">Professional Experience</h3>

        <div class="experience-section">
          <h4 class="company-name"><a href="https://9gag.com">9GAG</a> (2014 - Present)</h4>
          <p class="description">
            A social media platform where memes are serious business, and I've been making sure they load properly for over a decade.
          </p>

          <div class="timeline-item">
            <div class="timeline-year">2024-2025</div>
            <div class="timeline-content">
              <strong>Web3/AI R&D Engineer</strong><br>
              <ul class="achievement-list">
                <li>Pivoted to web3 and AI projects—because staying in one comfort zone is overrated</li>
                <li>Working in a team of 6 engineers on rapid prototyping and proof-of-concepts</li>
                <li>Tech stack: Next.js, Supabase, Cloudflare Workers + tRPC, Chakra UI, Tamagui, Tailwind</li>
                <li>Leveled up from just coding to prioritizing requirements and unblocking teammates</li>
                <li>Role: Full-stack implementation + product requirement prioritization + team technical support</li>
              </ul>
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-year">2021-2023</div>
            <div class="timeline-content">
              <strong>Senior Android Developer (Return of the Native)</strong><br>
              <ul class="achievement-list">
                <li>Returned to 9GAG Android after Flutter adventure</li>
                <li>Introduced Kotlin Multiplatform (KMP) for aligning business logic across platforms</li>
                <li>Applied lessons learned from Flutter to make KMP the sensible choice for multiplatform + legacy code support</li>
              </ul>
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-year">2020-2021</div>
            <div class="timeline-content">
              <strong>Solo Flutter Developer - Community App Project</strong><br>
              <ul class="achievement-list">
                <li>Built a proof-of-concept community app for local groups—solo mission mode activated</li>
                <li>Chose Flutter after the React Native experience (fool me once...)</li>
                <li>No prior knowledge of Dart or Flutter, but that's never stopped me before</li>
                <li>Successfully delivered cross-platform app in record time</li>
              </ul>
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-year">2017-2020</div>
            <div class="timeline-content">
              <strong>Senior Android Developer</strong><br>
              <ul class="achievement-list">
                <li>Introduced RxJava and ExoPlayer to the codebase—because callback hell is actually hell</li>
                <li>Completely rewrote post list and comment list loading architecture with RxJava</li>
                <li>Rebuilt image views into composable components for better maintainability</li>
                <li>Improved CI/CD pipeline and introduced Fastlane for automated Android app publishing</li>
                <li>Took ownership of critical user-facing features: image controls, video playback</li>
              </ul>
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-year">Mid-2017</div>
            <div class="timeline-content">
              <strong>React Native Experiment (The One That Got Away)</strong><br>
              <ul class="achievement-list">
                <li>Joined a team of 10 engineers to rewrite entire 9GAG app in React Native</li>
                <li>Zero prior React Native knowledge—but that's just a typical Tuesday at 9GAG</li>
                <li>Handled both frontend and native bridging, porting features from native codebase</li>
                <li>Project failed due to performance issues—valuable lesson: not all rewrites are meant to be</li>
              </ul>
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-year">2016-2017</div>
            <div class="timeline-content">
              <strong>Android Developer (The Unplanned Career Pivot)</strong><br>
              <ul class="achievement-list">
                <li>Transitioned from backend to Android when the previous developer left—because someone had to do it</li>
                <li>Zero Android development experience at start—100% learning-by-doing</li>
                <li>Completed migration from UniversalImageView to Facebook's Fresco</li>
                <li>Revamped entire post list loading architecture</li>
                <li>Worked solo initially, later scaled to team of 2</li>
              </ul>
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-year">2014-2016</div>
            <div class="timeline-content">
              <strong>Full-Stack Developer (The Beginning)</strong><br>
              <ul class="achievement-list">
                <li>Started in a team of 4 (1 PM, 2 backend, 1 frontend) on PHP-based projects</li>
                <li>Built 9GAG TV and 9CHAT using Laravel backend and JavaScript frontend</li>
                <li>Implemented XMPP-based chat service with Tigase server in team of 2</li>
                <li>Fun fact: Had zero knowledge of XMPP before starting—see a pattern here?</li>
              </ul>
            </div>
          </div>
        </div>

        <div class="experience-section">
          <h4 class="company-name">CargoSmart (2012 - 2014)</h4>
          <p class="description">
            <strong>Technical Analyst</strong><br>
            Started my professional journey maintaining enterprise systems and learning the ropes of software development.
          </p>
        </div>

        <h3 class="section-title">Core Competencies</h3>
        <p class="description">
          Over 10+ years, I've accumulated a rather eclectic tech stack. Here are the highlights:
        </p>
        <div class="skillset">
          <i class="ico fab fa-android fa-5x" title="Android"></i>
          <i class="ico fab fa-java fa-5x" title="Java"></i>
          <i class="ico fab fa-js-square fa-5x" title="JavaScript"></i>
          <i class="ico fab fa-react fa-5x" title="React/React Native"></i>
          <i class="ico fab fa-laravel fa-5x" title="Laravel"></i>
          <i class="ico fab fa-php fa-5x" title="PHP"></i>
          <i class="ico fab fa-node-js fa-5x" title="Node.js"></i>
        </div>
        <p class="description" style="margin-top: 1em; text-align: center; font-style: italic; color: #888;">
          Flutter • Kotlin • Kotlin Multiplatform • RxJava • Next.js • Supabase • Cloudflare Workers<br>
          tRPC • Tailwind • XMPP • ExoPlayer • CI/CD • Fastlane
        </p>

        <h3 class="section-title">What Makes Me Tick</h3>
        <p class="description">
          I'm that developer who says "I've never done this before" and then proceeds to ship it in production three weeks later. My superpower? Learning new technologies under pressure and actually enjoying it. Whether it's diving into XMPP with zero knowledge, becoming an Android developer overnight, or jumping into web3/AI, I've built my career on figuring things out on the fly.
        </p>
        <p class="description">
          In my spare time, I like reading, playing computer games (Hearthstone, Overwatch, Northgard or whatever's interesting), and wandering around shooting random photos. Because after debugging code all day, sometimes you just need to debug reality with a camera.
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

/* Career Profile Styles */
.section-title {
  color: #333;
  font-size: 1.5em;
  margin-top: 2em;
  margin-bottom: 1em;
  padding-bottom: 0.5em;
  border-bottom: 2px solid #e0e0e0;
}

.timeline-item {
  display: flex;
  margin-bottom: 1.5em;
  padding: 1em;
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: transform 0.2s, box-shadow 0.2s;
}

.timeline-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);
}

.timeline-year {
  font-weight: bold;
  color: #666;
  min-width: 100px;
  font-size: 1.1em;
  padding-right: 1em;
  border-right: 3px solid #4CAF50;
  margin-right: 1em;
}

.timeline-content {
  flex: 1;
  color: #444;
}

.timeline-content strong {
  color: #333;
  font-size: 1.1em;
}

.timeline-note {
  font-style: italic;
  color: #888;
  font-size: 0.9em;
}

.experience-section {
  margin-bottom: 2em;
}

.company-name {
  color: #2c3e50;
  font-size: 1.3em;
  margin-bottom: 0.5em;
  margin-top: 1.5em;
}

.company-name a {
  color: #4CAF50;
  text-decoration: none;
  transition: color 0.2s;
}

.company-name a:hover {
  color: #45a049;
  text-decoration: underline;
}

.achievement-list {
  list-style: none;
  padding-left: 0;
  margin-top: 0.5em;
}

.achievement-list li {
  padding-left: 1.5em;
  margin-bottom: 0.5em;
  position: relative;
  line-height: 1.6;
  color: #555;
}

.achievement-list li:before {
  content: "▸";
  position: absolute;
  left: 0;
  color: #4CAF50;
  font-weight: bold;
}

/* Responsive adjustments */
@media screen and (max-width: 600px) {
  .timeline-item {
    flex-direction: column;
  }

  .timeline-year {
    border-right: none;
    border-bottom: 2px solid #4CAF50;
    padding-bottom: 0.5em;
    margin-bottom: 0.5em;
    margin-right: 0;
  }

  .section-title {
    font-size: 1.3em;
  }
}

</style>
