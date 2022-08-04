<template>

    <div
    class="elative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded"
    :class="[color === 'light' ? 'bg-white' : 'bg-white text-black']"
  >
    <div class="rounded-t mb-0 px-4 py-3 border-0">
      <div class="flex flex-wrap items-center">
        <div class="relative w-full px-4 max-w-full flex-grow flex-1">
          <h3
            class="font-semibold text-lg"
            :class="[color === 'light' ? 'text-black' : 'text-black']"
          >
            Card Tables
          </h3>
        </div>
      </div>
    </div>
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
             Account Details
            </th>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            >
              Amount
            </th>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            >
              Phone Number
            </th>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            >
             Transfer Type
            </th>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            >
              Created By
            </th>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            >
              Initiated By
            </th>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            >
              Status
            </th>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            >
              Remark
            </th>
            <th
              class="px-6 align-middle border border-solid py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left"
              :class="[
                color === 'light'
                  ? 'bg-white text-blueGray-500 border-blueGray-100'
                  : 'bg-white text-black ',
              ]"
            ></th>
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
               <div class=" px-4 py-2flex flex-col">
                            <p class="text-sm font-bold">Musa John</p>
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
            <!-- <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              <div class="flex">
                <img
                  :src="team1"
                  alt="..."
                  class="w-10 h-10 rounded-full border-2 border-blueGray-50 shadow"
                />
                <img
                  :src="team2"
                  alt="..."
                  class="w-10 h-10 rounded-full border-2 border-blueGray-50 shadow -ml-4"
                />
                <img
                  :src="team3"
                  alt="..."
                  class="w-10 h-10 rounded-full border-2 border-blueGray-50 shadow -ml-4"
                />
                <img
                  :src="team4"
                  alt="..."
                  class="w-10 h-10 rounded-full border-2 border-blueGray-50 shadow -ml-4"
                />
              </div>
            </td> -->
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
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              Single
            </td>
            <td
              class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4"
            >
              Treated
            </td>
          </tr>

        </tbody>
      </table>
    </div>
  </div>
</template>

<script >
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
        name:"TableComponent",

    }
</script>

<style lang="sass" scoped>

</style>