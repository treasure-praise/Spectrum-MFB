<template>
    <div class="mx h-auto">
      <h1 class="mb-9  pt-12 text-[#3C3C3B] font-semibold text-2xl">{{BreadcrumbTitle}}/~</h1>
      <div>
        <h1 class="mb-6">Overview</h1>
        <div class="md:flex w-4/5 md:w-full mx-auto md:gap-6 mb-12">
          <div
            class="md:w-1/3 rounded-lg px-2 py-8 flex items-center border bg-[#F9EBBF] justify-center gap-6 mb-8 md:mb-0  hover:bg-[#FEDB6E]" 
          >
            <img src="../assets/icons/disc (1).png" alt="" />
            <h2 class="font-bold text-base text-[#3C3C3B]">
              Pending Transfers
            </h2>
            <span class="text-5xl font-bold text-[#3C3C3B]">2</span>
          </div>

          <div
            class="md:w-1/3 rounded-lg px-2 py-8 flex items-center border bg-[#93D0EA] justify-center gap-6 text-white mb-8 md:mb-0  hover:bg-[#0098DA]"
          >
            <img src="../assets/icons/disc.png" alt="" />
            <h2 class="font-bold text-base">Processed Transfers</h2>
            <span class="text-5xl font-bold">2</span>
          </div>

          <div
            class="md:w-1/3 rounded-lg px-2 py-8 flex items-center border bg-[#F2A7A9] justify-center gap-6 text-white mb-8 md:mb-0 hover:bg-[#ED3237]"
          >
            <img src="../assets/icons/alert-circle.png" alt="" />
            <h2 class="font-bold text-base">Rejected Transfers</h2>
            <span class="text-5xl font-bold">2</span>
          </div>
        </div>
      </div>
      <div>
        <div class="flex mb-10">
          <h2 class="font-bold text-[#171725] mr-2">All Transfers</h2>
          <div class="flex">
             <span >Sort: All<button class="items-center"> <i><img  src="../assets/icons/ic_Dropdown.svg" alt=""></i></button></span>
          </div>
            
            
          
         
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
    components: { TableComponent },
    props:['BreadcrumbTitle']
}
</script>

<style lang="scss" scoped>

</style>