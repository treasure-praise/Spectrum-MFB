<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
import SideBar from './components/SideBar.vue';
import Login from './pages/Login.vue';
import Dashboard from './pages/Dashboard.vue';
</script>

<template>
  <div class="flex">
    <!-- <Login/> -->
    <Dashboard/>
    <!-- <SideBar class="w-96 h-screen" /> -->
  
  </div>
  
</template>

<style>
#app {
  font-family: Poppins,  sans-serif;
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  }
</style>
