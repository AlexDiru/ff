<template>
  <HelloWorld msg="Welcome to Your Vue.js App"/>

  <div class="footer">
    <p>
      Coming soon (probably like 2025, and only if I ever get an actual idea)
    </p>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
body {
  background-color: #2c3e50;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #aaaaaa;
  margin-top: 60px;
}

.footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  text-align: center;
}
</style>
