<template>
    <v-app>
    <v-app-bar app clipped-left dark color="primary">
      <v-toolbar-title>The Pong Game</v-toolbar-title>
    </v-app-bar>
    <v-navigation-drawer app clipped class="purple ligthten-1"> </v-navigation-drawer>
    <v-content class="error noOverflow">
      <router-view />
    </v-content>
  </v-app>
</template>
