<template>
  <v-container fluid fill-height class="home-hero">
    <v-layout justify-center align-center column pt-5>
      <div class="display-2 font-weight-black white--text text-xs-center">HEALTHY MEALS</div>
      <div class="display-2 font-weight-black white--text text-xs-center mb-3">FOR YOUR TABLE</div>
      <div class="font-weight-bold white--text text-xs-center">lorem hdbdf bdfdj</div>
      <v-btn fab class="mt-5 blue darken-4">
        <v-icon color="white">mdi-arrow-down</v-icon>
      </v-btn>
    </v-layout>

    <!-- <v-fab-transition>
      <v-btn v-show="!hidden" color="pink" fab dark small absolute bottom left>
        <v-icon></v-icon>
      </v-btn>
    </v-fab-transition>-->
  </v-container>
</template>
<script>
export default {
  name: "HomeHero"
};
</script>

<style scoped>
.home-hero {
  /* background: url('/') */
  background: #2c2cc5;
  background-size: cover;
  width: 100%;
  height: 100%;
  max-height: 100vh;
  background-color: linear-gradient (to right, #2744e754, #1a32bbb3);
}
</style>
