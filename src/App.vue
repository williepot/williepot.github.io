<template>
  <v-app>
    <TheNavbar />
    <v-main>
      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import TheNavbar from "./components/TheNavbar.vue";

export default {
  name: "App",

  components: {
    HelloWorld,
    TheNavbar,
  },

  data: () => ({
    //
  }),
};
</script>
