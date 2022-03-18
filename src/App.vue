<template>
  <div>
    <Hero />
    <div class="spacer layer1"></div>
    <AboutMe />
    <div class="spacer layer2"></div>
    <ProfessionalHistory />

  </div>
</template>

<script>
  import Hero from './components/Hero.vue'
  import AboutMe from './components/AboutMe.vue'
  import ProfessionalHistory from './components/ProfessionalHistory.vue'

  export default {
    name: 'App',
    components: {
      Hero,
      AboutMe,
      ProfessionalHistory
    }
  }
</script>

<style>
  /* CUSTOM PROPERTIES */
  :root {
    --dark: #261D1A;
    --gray: #BFBFBD;
    --light: #ededed;
    --accent-red: #8C3737;
    font-size: 1.125em;
  }

  #app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    /* text-align: center; */
    color: var(--light);
  }

  body {
    margin: 0;
    background-color: var(--light) !important;
    font-family: 'Lato', sans-serif;
  }

  h1,
  h2 {
    font-family: 'Bebas Neue', sans-serif;
  }

  p {
    line-height: 1.875em;
  }

  section {
    min-height: 400px;
    padding: 100px 20vw;
  }

  section.flexed {
    position: relative;
    display: flex;
    flex-direction: column;
    /* justify-content: center; */
  }

  .spacer {
    aspect-ratio: 960/320;
    width: 100%;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }

  .spacer2 {
    width: 100%;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }

  .layer1 {
    background-image: url('./assets/wave1.svg');
  }

  .layer2 {
    background-image: url('./assets/wave2.svg');
  }

  @media (max-width: 575px) {
    #app {
      text-align: left;
    }
  }
</style>