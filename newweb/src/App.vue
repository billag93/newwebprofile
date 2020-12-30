<template>
  <v-app>
   <pheader></pheader>
    <v-main>
     <router-view></router-view>
    </v-main>
    <p-footer></p-footer>
  </v-app>
</template>

<script>
import PFooter from './components/Pfooter';
import Pheader from './components/Pheader.vue';
export default {
  name: "App",

  components: {
    Pheader,
    PFooter,
  
  },

    data: () => ({
    //
  })
};
</script>
