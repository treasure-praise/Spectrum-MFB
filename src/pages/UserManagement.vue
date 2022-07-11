<template>
    <div>
        <div class="flex mb-10">
          <h2 class="font-bold">All Transfers</h2>
          <span>Sort: All</span>
          <SearchBar/>
        </div>
        <div class="rounded-lg h-auto bg-white border-red">
          <Table class="w-full">
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
          </Table>
        </div>
      </div>
</template>

<script>
import Table from "../components/Table.vue";
import SearchBar from "../components/SearchBar.vue";
    
</script>

<style lang="scss" scoped>

</style>