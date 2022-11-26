<template>
    <v-app id="inspire">
      <v-navigation-drawer v-model="drawer">
        <!--  -->
      </v-navigation-drawer>
  
      <v-app-bar>
        <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
  
        <v-toolbar-title>Test Page</v-toolbar-title>
        <v-spacer />
          <theme-switcher />
      </v-app-bar>
  
      <v-main>
        <!--  -->
      </v-main>
    </v-app>
  </template>
  
  <script>
import ThemeSwitcher from '~~/components/Header/ThemeSwitcher.vue'
    export default {
  components: { ThemeSwitcher },
      data: () => ({ drawer: null }),
    }
  </script>