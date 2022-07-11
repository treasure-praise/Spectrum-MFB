<template>
    <div class="w-1/5  text-center h-screen">
        <div class="pl-9 pt-12 pb-12">
            <img alt="Spectrum MFB Logo" src="../assets/logo.svg" />
        </div>
        
        <div class="flex flex-col justify-around  ">
            <div class="flex flex-col mx-7">
                <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left flex">
                    <img src="../assets/icons/element-4.svg" alt="">
                <h2 c>Dashboard</h2>
                </div>
                
                <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left flex">
                    <img src="../assets/icons/note.svg" alt="">
                <h2 >Transfer Request</h2> 
                </div>
                
                <div class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left flex">
                    <img src="../assets/icons/users.svg" alt="">
                    <h2 >User Management</h2>
                </div>
                
                <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Report</h2>
                <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Messgae</h2>
                <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Settings</h2>
            </div>
            <div class="flex flex-col mx-7">
                <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Help</h2>
                <h2 class="hover:bg-[#0098DA] w-full hover:rounded mx-auto px-5 py-3 text-left">Logout</h2>
            </div>
        </div>
    </div>
</template>

<script setup>
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