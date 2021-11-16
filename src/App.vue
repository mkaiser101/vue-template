<template>
  <div id="app">
    <div id="nav">
       <v-app-bar
      app
      color="primary"
      dark
    >
      <v-toolbar dense class="teal">
      <v-toolbar-title dark>Toolbar title</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-btn flat light to="/" exact>home</v-btn>
        <v-btn flat dark to="/projects" exact>projects</v-btn>
        <v-btn flat light to="/about" exact>about</v-btn>
        <v-btn flat dark to="/timeline" exact>timeline</v-btn>
        <v-btn flat dark to="/cookbook" exact>cookbook</v-btn>
      </v-toolbar-items>
    </v-toolbar>
    </v-app-bar>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
