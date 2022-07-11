<template>
  <div class="bg-[#fafafa]  w-4/5 h-auto">
    <Navbar />
    <div class=" ml-20 mr-12 h-auto">
      <!-- <h1>Dashboard/~</h1> -->
      <h1>Profile/~</h1>
      <!-- <div>
        <h1>Overview</h1>
        <div class="flex gap-12">
          <div
            class="w-2/3 rounded-lg px-3 py-8 flex items-center border bg-[#F9EBBF] justify-center gap-6"
          >
            <img src="../assets/icons/disc (1).png" alt="" />
            <h2 class="font-bold text-base text-[#3C3C3B]">
              Pending Transfers
            </h2>
            <span class="text-5xl font-bold text-[#3C3C3B]">2</span>
          </div>

          <div
            class="w-2/3 rounded-lg px-3 py-8 flex items-center border bg-[#93D0EA] justify-center gap-6 text-white"
          >
            <img src="../assets/icons/disc.png" alt="" />
            <h2 class="font-bold text-base">Processed Transfers</h2>
            <span class="text-5xl font-bold">2</span>
          </div>

          <div
            class="w-2/3 rounded-lg px-3 py-8 flex items-center border bg-[#F2A7A9] justify-center gap-6 text-white"
          >
            <img src="../assets/icons/alert-circle.png" alt="" />
            <h2 class="font-bold text-base">Rejected Transfers</h2>
            <span class="text-5xl font-bold">2</span>
          </div>
        </div>
      </div> -->
      <!-- <div>
        <div class="flex mb-10">
          <h2 class="font-bold">All Transfers</h2>
          <span>Sort: All</span>
        </div>
        <div class="rounded-lg h-auto bg-white border-red">
          <Table />
        </div>
      </div> -->
        <Profile/>
        <!-- <ProfileEdit/> -->
   </div>
  </div>
</template>

<script setup>
import Navbar from "./Navbar.vue";
import Table from "./Table.vue";
import Profile from "../pages/Profile.vue";
import ProfileEdit from "../pages/ProfileEdit.vue";
</script>

<style lang="scss" scoped></style>
