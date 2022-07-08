<template>
  <div class="flex border h-screen ">
    <main class="w-1/2 ">
      <div class="w-2/3 mx-auto place-content-center my-24">
        <img src="../assets/logo.svg" alt="">
        <h1 class="text-5xl font-bold">Welcome Back</h1>
        <form class="mt-11 " action="">
          <div class="flex flex-col w-full align-top mb-10">
            <label
              class=" text-sm text-left mb-2"
              for="Email"
            >
              Email
            </label>
            <input class="bg-[#fafafa] w-full px-5 py-8 rounded-lg" type="email">
          </div>
          <div class="flex flex-col w-full align-top">
            <label
              class=" text-sm text-left mb-2"
              for="Password"
            >
              Password
            </label>
            <input class="bg-[#fafafa] w-full px-5 py-8 rounded-lg" type="password">
          </div>
          <div class="flex flex-col justify-between mt-7 h-2">
            <a href="" class="text-left">Forgot Password</a>
            <div>
                <button class="block p-4 rounded  float-right  font-bold w-24 justify-end bg-[#0098DA] text-white">Log in</button>
          </div>
          </div>
          
          
        </form>
      </div>
    </main>
    <div class="w-1/2 bg-[#0098DA]">
      <img class="h-auto mx-auto" src="../assets/Transfer@4x 1.svg" alt="hero-img" />
    </div>
  </div>
</template>

<script setup></script>

<style lang="css" scoped>
</style>
