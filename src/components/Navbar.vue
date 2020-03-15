<template>
  <div class="navbar">
    <v-app-bar color="deep-purple accent-4 v-app-bar" dense dark>
      <!-- <v-app-bar-nav-icon></v-app-bar-nav-icon> -->
      <v-toolbar-title class="title">Game Demo</v-toolbar-title>
      
      <v-spacer/>

      <div class="menu-section">
        <v-btn to="/" class="menu"><span>Home</span></v-btn>
        <v-btn to="/about" class="menu"><span>About</span></v-btn>
      </div>

    </v-app-bar>
  </div>
</template>

<style scoped>
.v-app-bar {
  background-color: #381403 !important;
}
.title {
  font-size: 24px;
  font-weight: bold;
}
.menu-section a {
  background-color: #5a270f !important;
  border: 2px solid #272727;
  margin: 4px;
  font-size: 16px;
  color: #FFF;
  font-weight: bold;
}
</style>