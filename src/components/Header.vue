<template>
  <v-app-bar app absolute class="transparent" :elevation="0">
    <v-toolbar-title>
      FreakProof
      <v-icon class="ml-1 mb-1 green--text">local_atm</v-icon>
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn icon to="/about">
      <v-icon>help_outline</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {
  name: "Header"
};
</script>
