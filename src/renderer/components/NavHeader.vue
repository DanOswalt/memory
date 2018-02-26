<template>
  <!-- <v-navigation-drawer app></v-navigation-drawer> -->
  <v-toolbar app flat>
    <v-toolbar-title>Memory!</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items>
      <v-btn flat primary>New Game</v-btn>
    </v-toolbar-items>
  </v-toolbar>
</template>

<script>
  export default {
    methods: {
      open (link) {
        this.$electron.shell.openExternal(link)
      }
    }
  }
</script>

<style>
</style>
