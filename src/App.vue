<template>
    <div id="app">
        <h1>This is the App Component</h1>
        <router-view></router-view>
    </div>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
    }
</style>
