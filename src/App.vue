<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Tikken</span>
        <span class="font-weight-light">'s table</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn flat href="https://github.com/vuetifyjs/vuetify/releases/latest" target="_blank">
        <span class="mr-2">Github</span>
      </v-btn>
    </v-toolbar>
    <v-content>
      <Table/>
    </v-content>
  </v-app>
</template>

<script>
import Table from "./components/Table.vue";

export default {
  name: "App",
  components: {
    Table
  },
  data() {
    return {
      //
    };
  }
};
</script>
