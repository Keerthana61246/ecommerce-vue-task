<template>
  <v-app :theme="$store.state.theme">
    <v-app-bar app>
      <v-toolbar-title>E-Commerce</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn @click="$store.commit('toggleTheme')">Toggle Theme</v-btn>
    </v-app-bar>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>