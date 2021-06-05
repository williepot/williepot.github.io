<template>
  <v-card class="overflow-hidden">
    <v-app-bar app tile dark color="grey darken-1">
      <v-app-bar-title>
        <div>LOGO</div>
      </v-app-bar-title>
      <v-spacer></v-spacer>
      <div class="d-none d-sm-flex">
        <v-btn text tile class="mr-3">about</v-btn>
        <v-btn text tile class="mr-3">skills</v-btn>
        <v-btn text tile class="mr-3">portfolio</v-btn>
        <v-btn text tile class="mr-3">contact</v-btn>
      </div>
      <v-app-bar-nav-icon class="d-sm-none"></v-app-bar-nav-icon>
    </v-app-bar>
  </v-card>
</template>

<script>
export default {
  name: "TheNavbar",
};
</script>