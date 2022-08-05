<template>

    <div
    class="elative  flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded"
    
  >

    <div class="block w-full  font-poppins overflow-x-auto">
      <!-- Projects table -->
      <table class="font-poppins text-[#6C82A3] items-center w-full bg-transparent border-collapse ">
        <thead class="">
          <tr>
            <th
              class="px-6 align-middle   py-3 text-xs uppercase border-r-0 whitespace-nowrap font-semibold text-left font-poppins"
            >
             Account Details
            </th>
            <th
              class="px-6 align-middle  py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              
            >
              Amount
            </th>
            <th
              class="px-6 align-middle py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              
            >
              Phone Number
            </th>
            <th
              class="px-6 align-middle  py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              
            >
             Transfer Type
            </th>
            <th
              class="px-6 align-middle  py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
             
            >
              Created By
            </th>
            <th
              class="px-6 align-middle py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
             
            >
              Initiated By
            </th>
            <th
              class="px-6 align-middle  py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              
            >
              Status
            </th>
            <th
              class="px-6 align-middle  py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
             
            >
              Remark
            </th>
            <th
              class="px-6 align-middle  py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              
            ></th>
          </tr>
        </thead>
        <tbody>
          <tr class="border border-solid border-l-0 ">
            <th
              class="border-t-0 px-6 align-middle  border-r-0 text-xs whitespace-nowrap p-4 text-left flex items-center "
            >
              <span
                
              >
               <div class=" px-4 py-2flex flex-col">
                            <p class="text-sm font-bold text-[#0A2E65]">Musa John</p>
                            <span class="text-xs">2056317233 (Uba Bank)</span>
                        </div>
              </span>
            </th>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              ₦ 100,200,000.30
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <i class="fas fa-circle text-orange-500 mr-2"></i> 07064394653
            </td>
             <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <div class="flex items-center gap-2">
                            <p class="text-sm font-bold">Single</p>
                            <span class="text-sm"><i><img src="../assets/icons/Single.svg" alt="" srcset=""></i></span>
                        </div>
              
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <div class="flex items-center">
                <span class="mr-2">13 Jan, 2022 12:01am</span>
                <div class="relative w-full">
                  <div
                    class="overflow-hidden h-2 text-xs flex rounded bg-red-200"
                  >
                    <div
                      style="width: 60%;"
                      class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-red-500"
                    ></div>
                  </div>
                </div>
              </div>
            </td>
            <!-- <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4 text-right"
            >
              <table-dropdown />
            </td> -->
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              Jude Ibrahim
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4 "
            >
              <StatusButton text="Success"/>

            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              Treated
            </td>
          </tr>

            <tr class="border border-solid border-l-0 ">
            <th
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4 text-left flex items-center"
            >
              <span
                class="ml-3 font-bold"
                
              >
               <div class=" px-4 py-2 flex flex-col">
                            <p class="text-sm font-bold text-[#0A2E65]">Musa John</p>
                            <span class="text-xs">2056317233 (Uba Bank)</span>
                        </div>
              </span>
            </th>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              ₦ 100,200,000.30
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <i class="fas fa-circle text-orange-500 mr-2"></i> 07064394653
            </td>
             <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <div class="flex items-center gap-2">
                            <p class="text-sm font-bold">Batch</p>
                            <span class="text-sm"><i><img src="../assets/icons/batch.svg" alt="" srcset=""></i></span>
                        </div>
              
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <div class="flex items-center">
                <span class="mr-2">13 Jan, 2022 12:01am</span>
                <div class="relative w-full">
                  <div
                    class="overflow-hidden h-2 text-xs flex rounded bg-red-200"
                  >
                    <div
                      style="width: 60%;"
                      class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-red-500"
                    ></div>
                  </div>
                </div>
              </div>
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              Jude Ibrahim
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4 "
            >
              <StatusButton text="Pending"/>

            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              Awaiting Overide
            </td>
          </tr>

          <tr class="border border-solid border-l-0 ">
            <th
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4 text-left flex items-center"
            >
              <span
                class="ml-3 font-bold"
                
              >
               <div class=" px-4 py-2 flex flex-col">
                            <p class="text-sm font-bold text-[#0A2E65]">Musa John</p>
                            <span class="text-xs">2056317233 (Uba Bank)</span>
                        </div>
              </span>
            </th>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              ₦ 100,200,000.30
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <i class="fas fa-circle text-orange-500 mr-2"></i> 07064394653
            </td>
             <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <div class="flex items-center gap-2">
                            <p class="text-sm font-bold">Single</p>
                            <span class="text-sm"><i><img src="../assets/icons/Single.svg" alt="" srcset=""></i></span>
                        </div>
              
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <div class="flex items-center">
                <span class="mr-2">13 Jan, 2022 12:01am</span>
                <div class="relative w-full">
                  <div
                    class="overflow-hidden h-2 text-xs flex rounded bg-red-200"
                  >
                    <div
                      style="width: 60%;"
                      class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-red-500"
                    ></div>
                  </div>
                </div>
              </div>
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              Jude Ibrahim
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4 "
            >
              <StatusButton text="Rejected"/>

            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              Incomplete Profile
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script >
import StatusButton from './StatusButton.vue'
   const items=[
        {
            'id':'1',
            'Beneficiary Name': 'Musa John',
            'Ammount': '₦ 100,200,000.30',
            'Account Number': '2020599742',
            'Bank': 'UBA',
            'Phone Number': '07064394653'
        },
        {
            'id':'2',
            'Beneficiary Name': 'Musa John',
            'Ammount': '₦ 100,200,000.30',
            'Account Number': '2020599742',
            'Bank': 'UBA',
            'Phone Number': '07064394653'
        },
        {
            'id':'3',
            'Beneficiary Name': 'Musa John',
            'Ammount': '₦ 100,200,000.30',
            'Account Number': '2020599742',
            'Bank': 'UBA',
            'Phone Number': '07064394653'
      },
    ]
    const columns= [ 'id', 'Beneficiary Name', 'Ammount', 'Account Number','Bank','Phone Number']

    export default {
    name: "TableComponent",
    components: { StatusButton }
}
</script>

<style lang="sass" scoped>

</style>