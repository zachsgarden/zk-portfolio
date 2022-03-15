<template>
  <div class="container">
    <Hero />
    <AboutMe />
  </div>
</template>

<script>
  import Hero from './components/Hero.vue'
  import AboutMe from './components/AboutMe.vue'

  export default {
    name: 'App',
    components: {
      Hero,
      AboutMe
    }
  }
</script>

<style>
  #app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }

  body {
    background-color: #ededed;
    font-family: 'Lato', sans-serif;
  }

  h1 {
    font-family: 'Bebas Neue', sans-serif;
  }

  @media (max-width: 575px) {
    #app {
      text-align: left;
    }
  }
</style>