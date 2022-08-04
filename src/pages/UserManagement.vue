<template>
    <div class="w-full">
        <div class="flex mb-10">
          <h2 class="font-bold">All Transfers</h2>
          <span>Sort: All</span>
          <SearchBar/>
        </div>
        <div class="rounded-lg h-auto bg-white border-red mx-auto">
          <!-- <Table class="w-full fixed">
            <thead class="border-b">
            <tr >
                <th class="px-4 py-2">ID</th>
                <th class="px-4 py-2">Team</th>
                <th class="px-4 py-2">Created at</th>
                <th class="px-4 py-2">Action</th>
            </tr>   
        </thead>
        <tbody>
            <tr class="border-b py-10">
                    <td>
                        <div class="flex items-center ">
                            <img class="w-20 h-20 rounded-lg m-6" src="../assets/courage 1.png" alt="">
                            <div class=" px-4 py-2flex flex-col">
                            <p class="text-lg font-bold ">Segun Oluwalana</p>
                            <p class="text-lg text-[#A5AAB6]  font-bold mb-1">Customer Care</p>
                            <p class="text-xs text-[#B4B7CC]">segun.oluwalana@gmail.com</p>
                        </div>
                        </div>
                    </td>
                    <td class="px-4 py-2 text-sm " >
                        <div class="flex gap-2">
                            <img src="../assets/icons/rectangle.svg" alt="">
                        <p>Default</p>
                        </div>
                        
                    </td>
                    <td class=" px-4 py-2 text-sm">2022-03-22T15:29:40.000000Z</td>
                    <td class="px-4 py-2 gap-8">
                        <div class="flex items-center gap-8">
                            <a href="#" class="flex gap-2 items-center">
                                <span class="text-sm"><i><img src="../assets/icons/Single.svg" alt="" srcset=""></i></span>
                            <p class="text-sm font-bold">Edit</p>
                            </a>
                             <a href="#" class="flex gap-2 items-center">
                                <span class="text-sm"><i><img src="../assets/icons/x-circle.svg" alt="" srcset=""></i></span>
                            <p class="text-sm font-bold">Deactivate</p>
                            </a>
                        </div>
                    </td>
            </tr>
            <tr class="border-b py-10">
                    <td>
                        <div class="flex items-center ">
                            <img class="w-20 h-20 rounded-lg m-6" src="../assets/courage 1.png" alt="">
                            <div class=" px-4 py-2flex flex-col">
                            <p class="text-lg font-bold ">Segun Oluwalana</p>
                            <p class="text-lg text-[#A5AAB6]  font-bold mb-1">Customer Care</p>
                            <p class="text-xs text-[#B4B7CC]">segun.oluwalana@gmail.com</p>
                        </div>
                        </div>
                    </td>
                    <td class="px-4 py-2 text-sm " >
                        <div class="flex gap-2">
                            <img src="../assets/icons/rectangle (1).svg" alt="">
                        <p class="text-[#6BB34B]">Loan</p>
                        </div>
                        
                    </td>
                    <td class=" px-4 py-2 text-sm">2022-03-22T15:29:40.000000Z</td>
                    <td class="px-4 py-2 gap-8">
                        <div class="flex items-center gap-8">
                            <a href="#" class="flex gap-2 items-center">
                                <span class="text-sm"><i><img src="../assets/icons/Single.svg" alt="" srcset=""></i></span>
                            <p class="text-sm font-bold">Edit</p>
                            </a>
                             <a href="#" class="flex gap-2 items-center">
                                <span class="text-sm"><i><img src="../assets/icons/x-circle.svg" alt="" srcset=""></i></span>
                            <p  class="text-sm font-bold">Deactivate</p>
                            </a>
                        </div>
                    </td>
                    
            </tr>
            <tr class="border-b py-10">
                    <td>
                        <div class="flex items-center ">
                            <img class="w-20 h-20 rounded-lg m-6" src="../assets/courage 1.png" alt="">
                            <div class=" px-4 py-2flex flex-col">
                            <p class="text-lg font-bold ">Segun Oluwalana</p>
                            <p class="text-lg text-[#A5AAB6]  font-bold mb-1">Customer Care</p>
                            <p class="text-xs text-[#B4B7CC]">segun.oluwalana@gmail.com</p>
                        </div>
                        </div>
                    </td>
                    <td class="px-4 py-2 text-sm " >
                        <div class="flex gap-2">
                            <img src="../assets/icons/rectangle (3).svg" alt="">
                        <p class="text-[#B33E2E]">Salary</p>
                        </div>
                        
                    </td>
                    <td class=" px-4 py-2 text-sm">2022-03-22T15:29:40.000000Z</td>
                    <td class="px-4 py-2 gap-8">
                        <div class="flex items-center gap-8">
                            <a href="#" class="flex gap-2 items-center">
                                <span class="text-sm"><i><img src="../assets/icons/Single.svg" alt="" srcset=""></i></span>
                            <p class="text-sm font-bold">Edit</p>
                            </a>
                             <a href="#" class="flex gap-2 items-center">
                                <span class="text-sm"><i><img src="../assets/icons/x-circle.svg" alt="" srcset=""></i></span>
                            <p class="text-sm font-bold">Deactivate</p>
                            </a>
                        </div>
                    </td>
                    
            </tr>
        </tbody>
          </Table> -->
        <div
    class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded"
    :class="[color === 'light' ? 'bg-white' : 'bg-white text-black']"
  >
    
    <div class="block w-full overflow-x-auto">
      <!-- Projects table -->
      <table class="items-center w-full bg-transparent border-collapse">
        <thead>
          <tr>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            >
             ID
            </th>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            >
              Team
            </th>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            >
              Created at
            </th>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            >
             Action
            </th>
         
          </tr>
        </thead>
        <tbody>
          <tr>
            <th
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4 text-left flex items-center"
            >
              <span
                class="ml-3 font-bold"
                :class="[
                  color === 'light' ? 'text-blueGray-600' : 'text-black',
                ]"
              >
               <div class="flex items-center ">
                            <img class="w-20 h-20 rounded-lg " src="../assets/courage 1.png" alt="">
                            <div class=" px-4 py-2flex flex-col">
                            <p class="text-lg font-bold ">Segun Oluwalana</p>
                            <p class="text-lg text-[#A5AAB6]  font-bold mb-1">Customer Care</p>
                            <p class="text-xs text-[#B4B7CC]">segun.oluwalana@gmail.com</p>
                        </div>
                </div>
              </span>
            </th>
        
 
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <div class="flex gap-2">
                            <img src="../assets/icons/rectangle.svg" alt="">
                        <p>Default</p>
            </div>
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              2022-03-22T15:29:40.000000Z
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <div class="flex items-center gap-8">
                            <a href="#" class="flex gap-2 items-center">
                                <span class="text-sm w-4"><i><img src="../assets/icons/Single.svg" alt="" srcset=""></i></span>
                            <p class="text-sm font-bold">Edit</p>
                            </a>
                             <a href="#" class="flex gap-2 items-center">
                                <span class="text-sm w-4"><i><img src="../assets/icons/x-circle.svg" alt="" srcset=""></i></span>
                            <p class="text-sm font-bold">Deactivate</p>
                            </a>
                        </div>
            </td>
          </tr>

        </tbody>
      </table>
    </div>
  </div>
        </div>
      </div>
</template>

<script>
import Table from "../components/Table.vue";


import SearchBar from '../components/SearchBar.vue';

export default {
    components: {
        SearchBar
    },
};
    
</script>

<style lang="scss" scoped>

</style>