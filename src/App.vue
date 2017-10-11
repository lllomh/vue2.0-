<template>
  <div id="app">
      <ul>
          <li>
              <router-link to="/Foo">Go to Foo</router-link>
              <router-link to="/Bar">Go to Bar</router-link>
          </li>
      </ul>
      <router-view></router-view>
       <Hello></Hello>
      <Hi></Hi>
  </div>
</template>

<script>

import Hello from './components/Hello.vue'
import Hi from './components/Hi.vue'
export default {
  name: 'app',
  components:{
      Hello,
      Hi
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0;
}
</style>
