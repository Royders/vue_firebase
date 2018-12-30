<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>This is an awesome </span>
        <span class="font-weight-light">Simple ToDo</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        flat
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-2">Latest Release</span>
      </v-btn>
    </v-toolbar>

    <v-content>
      <router-views> </router-views>
    </v-content>
  </v-app>
</template>

<script>


export default {
  name: 'App',
  data () {
    return {
      //
    }
  }
}
</script>
