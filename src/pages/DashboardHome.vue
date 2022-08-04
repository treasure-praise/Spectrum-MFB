<template>
    <div class="mx h-auto border">
      <h1 class="mb-9">{BreadcrumbTitle}/~</h1>
      <!-- <h1>Profile/~</h1> -->
      <div>
        <h1 class="mb-6">Overview</h1>
        <div class="md:flex w-2/3 md:w-full mx-auto md:gap-6 mb-12">
          <div
            class="md:w-1/3 rounded-lg px-2 py-8 flex items-center border bg-[#F9EBBF] justify-center gap-6 mb-8 md:mb-0"
          >
            <img src="../assets/icons/disc (1).png" alt="" />
            <h2 class="font-bold text-base text-[#3C3C3B]">
              Pending Transfers
            </h2>
            <span class="text-5xl font-bold text-[#3C3C3B]">2</span>
          </div>

          <div
            class="md:w-1/3 rounded-lg px-2 py-8 flex items-center border bg-[#93D0EA] justify-center gap-6 text-white mb-8 md:mb-0"
          >
            <img src="../assets/icons/disc.png" alt="" />
            <h2 class="font-bold text-base">Processed Transfers</h2>
            <span class="text-5xl font-bold">2</span>
          </div>

          <div
            class="md:w-1/3 rounded-lg px-2 py-8 flex items-center border bg-[#F2A7A9] justify-center gap-6 text-white mb-8 md:mb-0"
          >
            <img src="../assets/icons/alert-circle.png" alt="" />
            <h2 class="font-bold text-base">Rejected Transfers</h2>
            <span class="text-5xl font-bold">2</span>
          </div>
        </div>
      </div>
      <div>
        <div class="flex mb-10">
          <h2 class="font-bold">All Transfers</h2>
          <span>Sort: All</span>
        </div>
        <div class="rounded-lg h-full bg-white border-red">
         <TableComponent/>
        </div>
      </div>
  
      
      
      
    </div>
</template>

<script>


import TableComponent from "../components/TableComponent.vue";
    export default {
    components: { TableComponent }
}
</script>

<style lang="scss" scoped>

</style>