<template>
  <v-content>
    <v-container fluid>
      <v-layout row wrap>
        <!-- Board -->
        <board></board>
        <!-- Sidebar -->
        <sidebar></sidebar>
      </v-layout>
    </v-container>
  </v-content>
</template>

<script>
  import Board from '@/components/MainContent/Board'
  import Sidebar from '@/components/MainContent/Sidebar'

  export default {
    components: {
      Board,
      Sidebar
    }
  }
</script>

<style scoped>

</style>
