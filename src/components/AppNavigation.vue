<template>
  <span class="mt-1 p-3">
    <v-navigation-drawer app v-model="drawer" class="blue lighten-3" dark disable-resize-watcher>
      <v-list>
        <v-list-item v-for="item in items" :key="item.title" link>
          <v-list-item-content class="hidden-md-and-up">
            <v-list-item-title class="ml-5 py-3">{{ item.title }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-toobar app color="blue darken-4" dark>
      <v-row class="mx-1 hidden-md-and-up">
        <v-toolbar-title>{{ appTitle }}</v-toolbar-title>
        <v-spacer class="hidden-md-and-up"></v-spacer>
        <v-app-bar-nav-icon @click=" drawer = !drawer "></v-app-bar-nav-icon>
      </v-row>
      <!-- <v-spacer></v-spacer> -->
      <v-row class="hidden-sm-and-down mx-5 py-2">
        <router-link to="/">
          <v-toolbar-title>{{ appTitle }}</v-toolbar-title>
        </router-link>
        <v-btn flat to="/menu">Menu</v-btn>
        <v-spacer></v-spacer>
        <v-btn to="/signin" flat>SIGN IN</v-btn>
        <v-btn color="brown lighten-3" class="ml-6" to="/join">JOIN</v-btn>
      </v-row>
    </v-toobar>
  </span>
</template>

<script>
export default {
  name: "AppNavigation",
  data() {
    return {
      appTitle: "Meal Prep",
      drawer: false,
      items: [{ title: "Menu" }, { title: "Sign In" }, { title: "Join" }]
    };
  }
};
</script>

<style scoped></style>
