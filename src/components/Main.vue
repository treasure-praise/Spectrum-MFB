<template>
  <div class="bg-[#fafafa] w-full md:w-4/5  h-full md:px-8  px-4 overflow-y-scroll">
    <!-- <Navbar /> -->
    <div class=" h-auto overflow-y-scroll">
      <div class="flex justify-between md:hidden">
        <img src="../assets/logo.svg" alt="">
        <button
        class="cursor-pointer text-black opacity-50 md:hidden px-3 py-1 text-xl leading-none bg-transparent rounded border border-solid border-transparent"
        type="button"
        v-on:click="toggleCollapseShow('bg-white m-2 py-3 px-6')"
      >
      Buuton
        <i class="fas fa-bars"></i>
      </button>
      

      </div>
      <div
        class="md:flex md:hidden md:flex-col md:items-stretch md:opacity-100 md:relative md:mt-4 md:shadow-none shadow absolute top-0 left-0 right-0 z-40 overflow-y-auto overflow-x-hidden h-auto items-center flex-1 rounded "
        v-bind:class="collapseShow"
      >
        <!-- Collapse header -->
        <div
          class="md:hidden md:min-w-full block pb-4 mb-4 border-b border-solid border-blueGray-200"
        >
          <div class="flex flex-wrap">
            <div class="w-6/12">
              <router-link
                class="md:block text-left md:pb-2 text-blueGray-600 mr-0 inline-block whitespace-nowrap text-sm uppercase font-bold p-4 px-0"
                to="/"
              >
                Spectrum MFB
              </router-link>
            </div>
            <div class="w-6/12 flex justify-end">
              <button
                type="button"
                class="cursor-pointer text-black opacity-50 md:hidden px-3 py-1 text-xl leading-none bg-transparent rounded border border-solid border-transparent"
                v-on:click="toggleCollapseShow('hidden')"
              >
                <i class="fas fa-times"></i>
                Close
              </button>
            </div>
          </div>
        </div>
        <!-- replace with Navbar component -->
        <!-- Form  -->
        <!-- <form class="mt-6 mb-4 md:hidden">
          <div class="mb-3 pt-0">
            <input
              type="text"
              placeholder="Search"
              class="border-0 px-3 py-2 h-12 border border-solid border-blueGray-500 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-base leading-snug shadow-none outline-none focus:outline-none w-full font-normal"
            />
          </div>
        </form> -->
        <SearchBar/>
        <!-- Divider -->
        <hr class="my-4 md:min-w-full" />
        <!-- Heading -->
        <!-- <h6
          class="md:min-w-full text-blueGray-500 text-xs uppercase font-bold block pt-1 pb-4 no-underline"
        >
          Admin Layout Pages
        </h6> -->
        <!-- Navigation -->

        <ul class="md:flex-col md:min-w-full flex flex-col list-none">
          <li class="items-center">
            <!-- <router-link
              to="/admin/dashboard"
              v-slot="{ href, navigate, isActive }"
            >
              <a
                :href="href"
                @click="navigate"
                class="text-xs uppercase py-3 font-bold block"
                :class="[
                  isActive
                    ? 'text-emerald-500 hover:text-emerald-600'
                    : 'text-blueGray-700 hover:text-blueGray-500',
                ]"
              >
                <i
                  class="fas fa-tv mr-2 text-sm"
                  :class="[isActive ? 'opacity-75' : 'text-blueGray-300']"
                ></i>
                Dashboard
              </a>
            </router-link> -->
         <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left flex">
                    <img src="../assets/icons/element-4light.svg" alt="">
                <h2 class="px-5 text-base">Dashboard</h2>
                </div>
         </li>

          <li class="items-center">
          <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left flex">
                    <img src="../assets/icons/note.svg" alt="">
                <h2 class="pl-5 text-base">Transfer Request</h2> 
                </div>
         </li>

<li class="items-center">
          <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left flex">
                    <img src="../assets/icons/users.svg" alt="">
                    <h2 class="pl-5 ">User Management</h2>
                </div>
         </li>

         <li class="items-center">
          <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 text-left flex">
                    <img src="../assets/icons/document-text.svg" alt="">
                    <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Approver</h2>
                </div>
         </li>

         <li class="items-center">
          <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5  text-left flex">
                    <img src="../assets/icons/message.svg" alt="">
                    <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Messgae</h2>
                </div>
         </li>

         <li class="items-center">
          <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5  text-left flex">
                    <img src="../assets/icons/setting-2.svg" alt="">
                     <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Settings</h2>
                </div>   
         </li>
         <li class="items-center">
          <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5  text-left flex">
                    <img src="../assets/icons/Question.svg" alt="">
                     <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Help</h2>
                </div>
         </li>
         <li class="items-center">
          <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 text-left flex">
                    <img src="../assets/icons/SignOut.svg" alt="">
                     <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Logout</h2>
                </div>  
         </li>
          
        </ul>
    </div>
      
       <DashboardHome/>
      <Profile/>
      <ProfileEdit/>
      <UserManagement/>
      <UserManagementEdit/>

      <SingleTransactionApproval/>
      <BatchTransactionApproval/>
      <TableComponent/>
      <SingleTransferRequest/>
      <StatusModal/>
     
<SingleTransferRequestSummary/>

      <BatchTransferRequest/>

      <WorkspaceView/>
      <TransferRequestSent/>
      <BatchTransferRequestSummary/>
    </div>
  </div>
</template>

<script >



import DashboardHome from "../pages/DashboardHome.vue";
import Profile from "../pages/Profile.vue";
import ProfileEdit from "../pages/ProfileEdit.vue";
import UserManagement from "../pages/UserManagement.vue";
import UserManagementEdit from "../pages/UserManagementEdit.vue";
import SingleTransactionApproval from "../Modals/SingleTransactionApproval.vue";
import BatchTransactionApproval from "../Modals/BatchTransactionApproval.vue";
import TableComponent from "./TableComponent.vue";
import SingleTransferRequest from "../pages/SingleTransferRequest.vue";
import StatusModal from "../Modals/StatusModal.vue";
import BatchTransferRequest from "../pages/BatchTransferRequest.vue";
import WorkspaceView from "../pages/WorkspaceView.vue";
import TransferRequestSent from "../Modals/TransferRequestSent.vue";
import BatchTransferRequestSummary from "../Modals/BatchTransferRequestSummary.vue";
import SingleTransferRequestSummary from "../Modals/SingleTransferRequestSummary.vue";
import SearchBar from "./SearchBar.vue";


export default {
  data() {
    return {
      collapseShow: "hidden",
    };
  },
  methods: {
    toggleCollapseShow: function (classes) {
      this.collapseShow = classes;
    },
  },
  components: {
    DashboardHome,
    Profile,
    ProfileEdit,
    UserManagement,
    UserManagementEdit,
    SingleTransactionApproval,
    BatchTransactionApproval,
    TableComponent,
    SingleTransferRequest,
    StatusModal,
    BatchTransferRequest,
    WorkspaceView,
    TransferRequestSent,
    BatchTransferRequestSummary,
    SingleTransferRequestSummary,
    SearchBar
},
};
</script>

<style lang="scss" scoped></style>
