<script lang="ts">

import Notes from './components/Notes.vue'
import Example from './components/Example.vue'
import Bar from './components/Bar.vue'
import Pie from './components/Pie.vue'
import Stream from './components/Stream.vue'
/*
import ExampleWithLegend from './components/ExampleWithLegend.vue';
import ExampleWithInteractions from './components/ExampleWithInteractions.vue';*/

export default {
  components: {
    Notes,
    Example,
    Bar,
    Pie,
    Stream,
    /*
    ExampleWithLegend,
    ExampleWithInteractions*/
  }
}
</script>

<!--This is using the grid component from Vuetify to do layout design-->
<template>
  <!-- <v-container id="main-container" class="d-flex flex-column flex-nowrap" fluid> -->
  <v-container id="main-container">
    <!-- <v-row no-gutters>
      <v-col cols="5">
        <Example />
      </v-col>
    </v-row> -->
    <!-- <v-row no-gutters>
      <v-col>
        <Notes />
      </v-col>
    </v-row> -->
    <!-- <v-row no-gutters>
      <v-col>
        <Bar />
      </v-col>
    </v-row>
    <v-row no-gutters>
      <v-col>
        <Pie />
      </v-col>
    </v-row> -->
    <v-row no-gutters>
      <v-col>
        <Stream />
      </v-col>
    </v-row>
    <!-- <v-row no-gutters>
      <v-col>
        <text style="font-weight:bold">
          Region Note:
          1-North America
          2-Central America & Caribbean
          3-South America
          4-East Asia
          5-Southeast Asia
          6-South Asia
          7-Central Asia
          8-Western Europe
          9-Eastern Europe
          10-Middle East & North Africa
          11-Sub-Saharan Africa
          12-Australasia & Oceania
        </text>
      </v-col>
    </v-row> -->
    <br>
  </v-container>
</template>

<style scoped>
#main-container {
  height: 100%;
}
</style>
