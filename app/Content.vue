<template>
  <div id="app">
    <navbar></navbar>
    <cover></cover>
    <upcoming></upcoming>
    <recipe></recipe>
    <philosophy></philosophy>
    <goals></goals>
    <action></action>
    <team></team>
    <contact></contact>
    <footer></footer>
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Cover from './components/Cover'
import Upcoming from './components/Upcoming'
import Recipe from './components/Recipe'
import Philosophy from './components/Philosophy'
import Goals from './components/Goals'
import Action from './components/Action'
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
    Action,
    Team,
    Contact,
    Footer
  }
}
</script>

<style>
</style>

