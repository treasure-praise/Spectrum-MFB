<template>
  <div>
    <h1 class="mb-9 mt-12 text-[#3C3C3B] font-semibold text-2xl">{{BreadcrumbTitle}}/{{subTitle}}</h1>
  </div>

  <div class="md:flex w-full items-start border-b mb-10  md:mx-0">
    
    <div class="flex flex-col mt-4 md:w-1/2 mx-4 md:mx-0 ">
      <h2 class="text-[#0A2E65] font-bold text-lg mb-1">Profile Information</h2>
      <p class="text-[#6C82A3] text-sm mb-6">
        Update your account profile <br />
        information and email address
      </p>
    </div>
    <div class="md:flex  md:w-1/2 mx-4 md:mx-0 gap-10">
      <div class="">
        <form class="h-auto w-full" action="">
          <div class="flex flex-col w-full align-top mb-10">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for="Name">
              Name
            </label>
            <input
              class="bg-[#F5F6FA] h-16 md:w-80 w-full px-8 text-[#0A2E65] border rounded-md"
              type="text"
              placeholder="lorem ispum"
            />
          </div>
          <div class="flex flex-col w-full align-top">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for="Email">
              Email
            </label>
            <input
              class="bg-[#F5F6FA] text-[#0A2E65] border rounded-md h-16 md:w-80 w-full px-8"
              type="email"
              placeholder="loremispum@gmail.com"
            />
          </div>
          <div class="flex flex-col text-center justify-between my-7 ">
            <div>
              <button
                class="block p-1 rounded text-center font-bold w-20 h-12 justify-end bg-[#0098DA] text-white"
              >
                Save
              </button>
            </div>
          </div>
        </form>
      </div>
      <div class="flex flex-col text-[#0A2E65]">
        <img class="md:w-32 md:h-32 w-32  rounded-md" src="../assets/courage 1.png " alt="" />
        <a class="underline font-bold" href="">Change Picture</a>
      </div>
    </div>
  </div>

  <div class="md:flex w-full items-start h-full border-b mb-10  md:mx-0">
    <div class="flex flex-col mt-4 md:w-1/2 mx-4 md:mx-0">
      <h2 class="text-[#0A2E65] font-bold text-lg mb-1">Update Password</h2>
      <p class="text-[#6C82A3] text-sm mb-6">
        Ensure your account is using a long, <br />
        random password to stay secure.
      </p>
    </div>
    <div class="md:flex  md:w-1/2 mx-4 md:mx-0 gap-10">
      <div class="">
        <form class="h-auto w-full" action="">
          <div class="flex flex-col w-full align-top mb-10">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for="Name">
              Current Passowrd
            </label>
            <input
              class="bg-[#F5F6FA] h-16 md:w-80 w-full px-8 text-[#0A2E65] border rounded-md"
              type="text"
              placeholder="lorem ispum"
            />
          </div>
          <div class="flex flex-col w-full align-top mb-10">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for="Email">
              New Passwrod
            </label>
            <input
              class="bg-[#F5F6FA] text-[#0A2E65] border rounded-md h-16 md:w-80 w-full px-8"
              type="email"
              placeholder="loremispum@gmail.com"
            />
          </div>
          <div class="flex flex-col w-full align-top mb-10">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for="Name">
              Confirm New Passowrd
            </label>
            <input
              class="bg-[#F5F6FA] h-16 md:w-80 w-full px-8 text-[#0A2E65] border rounded-md"
              type="text"
              placeholder="lorem ispum"
            />
          </div>
          <div class="flex flex-col text-center justify-between my-7 ">
            <div>
              <button
                class="block p-1 rounded text-center font-bold w-20 h-12 justify-end bg-[#0098DA] text-white"
              >
                Save
              </button>
            </div>
          </div>
        </form>
      </div>
     
    </div>
  </div>

  <div class="md:flex w-full items-start h-full border-b pb-8 mb-10 md:mx-0">
    <div class="flex flex-col mt-4 md:w-1/2 mx-4 md:mx-0">
      <h2 class="text-[#0A2E65] font-bold text-lg mb-1">
        Two Factor Authentication
      </h2>
      <p class="text-[#6C82A3] text-sm">
        Add additional level of security to your account <br />
        using 2 Factor Authentication
      </p>
    </div>
    <div class="flex flex-col md:w-1/2 mx-4">
      <h3 class="text-[#6C82A3] text-sm mb-2">2FA</h3>
      <div class="flex gap-12 h-full rounded-lg border py-6 px-8">
        <div class="w-full flex flex-col">
          <h2 class="text-[#0A2E65] font-bold text-lg mb-2">
            You have not enabled two Factor Authentication
          </h2>
          <p class="text-[#6C82A3] text-sm mb-5">
            When 2FA is enabled, you will be prompted for a secure, random
            token. You may retrive this token from your linked Google
            Aunthenticator App.
          </p>
          <button
            class="block p-1 rounded text-center w-20 h-12 justify-end bg-[#0098DA] font-bold text-white"
          >
            Enable
          </button>
        </div>
      </div>
    </div>
  </div>

  <div class="md:flex w-full items-start h-full border-b pb-8 mb-10  md:mx-0">
    <div class="flex flex-col mt-4 md:w-1/2 mx-4 md:mx-0">
      <h2 class="text-[#0A2E65] font-bold text-lg mb-1">
        Two Factor Authentication
      </h2>
      <p class="text-[#6C82A3] text-sm">
        Add additional level of security to your account <br />
        using 2 Factor Authentication
      </p>
    </div>
    <div class="flex flex-col md:w-1/2 mx-4">
      <h3 class="text-[#6C82A3] text-sm mb-2">2FA</h3>
      <div class="flex gap-12 h-full rounded-lg border py-6 px-8">
        <div class="w-full flex flex-col">
          <h2 class="text-[#0A2E65] font-bold text-lg mb-2">
            You have not enabled two Factor Authentication
          </h2>
          <p class="text-[#6C82A3] text-sm mb-5">
            When 2FA is enabled, you will be prompted for a secure, random
            token. You may retrive this token from your linked Google
            Aunthenticator App.
          </p>
          <img class="w-44 h-44 pb-4" src="../assets/SGVsbG8= 1.svg" alt="">
          <div class="bg-white border py-4  px-4 rounded-md mb-6">
            <p class="text-[#6C82A3] text-sm mb-5">8453ngjkv9394gm30g00240g--4g2-4gn94903-4-4</p>
            <p class="text-[#6C82A3] text-sm mb-5">8453ngjkv9394gm30g00240g--4g2-4gn94903-4-4</p>
            <p class="text-[#6C82A3] text-sm mb-5">8453ngjkv9394gm30g00240g--4g2-4gn94903-4-4</p>
          </div>
          <div class="flex gap-8">
            <button
            class="block p-1 rounded text-center w-3/4 h-12 justify-end border bg-white font-bold text-[#0A2E65]"
          >
            Regenerate Recovery Codes
          </button>
            <button
            class="block p-1 rounded text-center w-20 h-12 justify-end bg-[#ED3237] font-bold text-white"
          >
            Disable
          </button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="md:flex w-full items-start h-full border-b pb-8 mb-10 md:mx-0">
    <div class="flex flex-col mt-4 md:w-1/2 mx-4 md:mx-0">
      <h2 class="text-[#0A2E65] font-bold text-lg mb-1">Browser Sessions</h2>
      <p class="text-[#6C82A3] text-sm">
        Manage and log out your active sessions on other <br />
        devices and browsers.
      </p>
    </div>

    <div class="md:flex flex-col md:w-1/2 mx-4">
      <h3 class="text-[#6C82A3] text-sm mb-2">Browsers and Devices</h3>
      <div class="flex gap-12 h-full rounded-lg border  py-6 px-8">
        <div class="w-full flex flex-col">
         
          <p class="text-[#6C82A3] text-sm mb-5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat.
          </p>
          <button
            class="block p-1 rounded text-center md:w-4/5 h-12 justify-end bg-[#0098DA] font-bold text-white"
          >
            Logout other Browser sessions
          </button>
        </div>
      </div>
    </div>
  </div>

  <div class="md:flex w-full items-start h-full border-b pb-8 mb-10 md:mx-0">
    <div class="flex flex-col mt-4 md:w-1/2 mx-4 md:mx-0">
      <h2 class="text-[#0A2E65] font-bold text-lg mb-1">Delete Account</h2>
      <p class="text-[#6C82A3] text-sm">
        Permanently delete your account
      </p>
    </div>
    <div class="flex flex-col md:w-1/2 mx-4">
      <h3 class="text-[#6C82A3] text-sm mb-2">Delete</h3>
      <div class="flex gap-12 h-full rounded-lg border py-6 px-8">
        <div class="w-full flex flex-col">
         
          <p class="text-[#6C82A3] text-sm mb-5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat.
          </p>
          <button
            class="block p-1 rounded text-center md:w-1/5 h-12 justify-end bg-[#ED3237] font-bold text-white"
          >
            Delete 
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props:['BreadcrumbTitle','subTitle']
};
</script>

<style lang="scss" scoped></style>
