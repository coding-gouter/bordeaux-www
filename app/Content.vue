<template>
  <div id="app">
    <img class="logo" src="assets/logo.png">
    <cover></cover>
    <p>
      Welcome to your Vue.js app. To get started, take a look at the
      <a href="https://github.com/vuejs-templates/webpack#folder-structure" target="_blank">README</a>
      of this template. If you have any issues with the setup, please file an issue at this template's repository.
    </p>
    <p>
      For advanced configurations, checkout the docs for
      <a href="http://webpack.github.io/" target="_blank">Webpack</a> and
      <a href="http://vuejs.github.io/vue-loader/" target="_blank">vue-loader</a>.
    </p>
    <p>
      You may also want to checkout
      <a href="https://github.com/vuejs/vue-router/" target="_blank">vue-router</a> for routing and
      <a href="https://github.com/vuejs/vuex/" target="_blank">vuex</a> for state management.
    </p>
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Cover from './components/Cover'
import Upcoming from './components/Upcoming'
import Recipe from './components/Recipe'
import Philosophy from './components/Philosophy'
import Goals from './components/Goals'
import Team from './components/Team'
import Contact from './components/Contact'
import Footer from './components/Footer'


export default {
  components: {
    Navbar,
    Cover,
    Upcoming,
    Recipe,
    Philosophy,
    Goals,
    Team,
    Contact,
    Footer,
  }
}
</script>

<style>
html {
  height: 100%;
}

body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}

#app {
  margin-top: -100px;
  max-width: 600px;
  font-family: Helvetica, sans-serif;
  text-align: center;
}

.logo {
  width: 100px;
  height: 100px
}
</style>
