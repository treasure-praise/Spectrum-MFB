<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
import SideBar from './components/SideBar.vue';
import Dashboard from './components/Dashboard.vue';
import Login from './pages/Login.vue';
</script>

<template>
  <div class="flex">
    <!-- <Login/> -->
    <SideBar class="w-96 h-screen" />
  <Dashboard class= "bg-[#fafafa] w-full"/>
  </div>
  
</template>

<style>
#app {
  font-family: Poppins,  sans-serif;
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  }
</style>
