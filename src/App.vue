<template>
  <div id="app">
    <app-header></app-header>
    <app-about></app-about>
    <app-projects></app-projects>
    <app-skills></app-skills>
    <app-contact></app-contact>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import Projects from './components/Projects.vue'
import Skills from './components/Skills.vue'
import Contact from './components/Contact.vue'

export default {
  components: {
    appHeader: Header,
    appAbout: About,
    appProjects: Projects,
    appSkills: Skills,
    appContact: Contact
  },
}
</script>

<style lang="scss">
  $main: #F6F5F5;

  html {
    scroll-behavior: smooth;
  }

  body {
    background-color: $main;
  }

  

</style>
