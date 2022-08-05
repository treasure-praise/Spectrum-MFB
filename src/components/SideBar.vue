<template>
    <div class=" hidden border  text-center h-screen bg-white overflow-y-auto overflow-hidden relative  md:block ">
        <div class="pl-9 pt-12 pb-12">
            <img alt="Spectrum MFB Logo" src="../assets/logo.svg" />
        </div>
        
        <div class="flex flex-col justify-around  ">
            <div class="flex flex-col mx-7">
                <div class="bg-[#0098DA] rounded w-full hover:rounded mx-auto px-5 py-3 text-left flex">
                    <img src="../assets/icons/element-4light.svg" alt="">
                <h2 class="px-5 text-base">Dashboard</h2>
                </div>
                
                <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left flex">
                    <img src="../assets/icons/note.svg" alt="">
                <h2 class="pl-5 text-base">Transfer Request</h2> 
                </div>
                
                <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left flex">
                    <img src="../assets/icons/users.svg" alt="">
                    <h2 class="pl-5 ">User Management</h2>
                </div>

                 <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 text-left flex">
                    <img src="../assets/icons/document-text.svg" alt="">
                    <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Approver</h2>
                </div>
                
                <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5  text-left flex">
                    <img src="../assets/icons/message.svg" alt="">
                    <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Messgae</h2>
                </div>

                <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5  text-left flex">
                    <img src="../assets/icons/setting-2.svg" alt="">
                     <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Settings</h2>
                </div>            
               
            </div>
            <div class="flex flex-col mx-7">

                <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5  text-left flex">
                    <img src="../assets/icons/Question.svg" alt="">
                     <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Help</h2>
                </div>

            <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 text-left flex">
                    <img src="../assets/icons/SignOut.svg" alt="">
                     <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Logout</h2>
                </div>
                
                
            </div>
        </div>
     
    </div>
</template>

<script >
import DashboardIcon from "../assets/icons/element-4.svg"
import TransferRequestIcon from "../assets/icons/note.svg"
import UserManagementIcon from "../assets/icons/users.svg"
import ReportIcon from "../assets/icons/document-text.svg"
import MessageIcon from "../assets/icons/message.svg"
import SettingsIcon from "../assets/icons/setting-2.svg"


const menu =[
    {name:"Dashboard", icon:DashboardIcon},
    {name:"TransferRequest", icon:TransferRequestIcon},
    {name:"UserManagement", icon:UserManagementIcon},
    {name:'Report', icon:ReportIcon},
    {name:'Message', icon: MessageIcon},
    {name:'Settings', icon: SettingsIcon}
]



</script>

<style lang="scss" scoped>

</style>