<template>
  <div>
    <header-component />
    <div class="app">
      <router-view></router-view>
    </div>
  </div>
  
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
  export default {
    components: {
      HeaderComponent
    }
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.app {
  padding: 1.5rem;
}
</style>
