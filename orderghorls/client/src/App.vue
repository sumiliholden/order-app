<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Order</router-link> |
      <router-link to="/all_orders">All Orders</router-link>
    </div>
    <b-container>
      <router-view />
    </b-container>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

}
</style>
