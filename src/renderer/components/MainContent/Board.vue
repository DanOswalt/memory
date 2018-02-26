<template>
  <v-flex xs7 text-xs-center>
    <v-card dark>
      <v-card-text class="px-0">{{ msg }}</v-card-text>
      <v-container fluid grid-list-xs>
        <v-layout row wrap>
          <v-flex
            xs2
            v-for="n in 36"
            :key="n"
          >
            <v-card class="facedown"
                    width="80px"
                    height="80px"
            >
            </v-card>
          </v-flex>
        </v-layout>
      </v-container>
    </v-card>
  </v-flex>
</template>

<script>
  export default {
    data: () => ({
      msg: 'Hello'
    })
  }
</script>

<style scoped>
  .facedown {
    background: tomato;
    cursor: pointer;
    border: #222 2px solid;
    border-radius: 5px;
  }
  .facedown:hover {
    border: green 4px solid;
  }
</style>
