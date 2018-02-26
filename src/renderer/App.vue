<template>
  <div id="app">
    <div id="wrapper">
      <v-app dark>
        <nav-header></nav-header>
        <main-content></main-content>
        <v-footer app></v-footer>
      </v-app>
    </div>
  </div>
</template>

<script>
  import NavHeader from '@/components/NavHeader'
  import MainContent from '@/components/MainContent'

  export default {
    name: 'memory',
    components: {
      NavHeader,
      MainContent
    }
  }
</script>

<style>
  /* CSS */
</style>
