<template>
  <div class="w-full bg-[#fafafa]">
    <h1 class="mb-9 pt-12 text-[#3C3C3B] font-semibold text-2xl">
      {{ BreadcrumbTitle }}/{{subTitle}}
    </h1>
    <h2 class="mb-9 pt-12 text-[#3C3C3B] font-semibold text-2xl">My Workspace</h2>
    <div class=" md:gap-8 flex flex-wrap md:w-full">
      <WorkspaceItems text="Delayed Bulk Payment" imgUrl="../assets/icons/delayed.svg" />

      <WorkspaceItems text="Transactions Approval" />
      <WorkspaceItems
        text="Pending Approvals (Non-transaction)"
      />
      <WorkspaceItems
        text="Pension Approval"
      />
      <WorkspaceItems
        text="Upload Pension Transaction"
      />
      <WorkspaceItems
        text="Delete Pension Schedule"
      />
      <WorkspaceItems
        text="Upload Dangote Transaction"
      />
      <WorkspaceItems
        text="Dangote Approval"
      />
      <WorkspaceItems
        text="Seven-up Transactions"
      />
      <WorkspaceItems
        text="Approve Seven-up Transactions"
      />
    </div>
  </div>
</template>

<script>
import WorkspaceItems from "../components/WorkspaceItems.vue";

const url ="./assets/icons/delayed.svg"
const urls = [
  {
    id:1,
    url:"../assets/icons/delayed.svg"
  }
]
export default {
  components: { WorkspaceItems },
  props:['BreadcrumbTitle', 'subTitle']
};
</script>

<style lang="scss" scoped></style>
