<template>
  <div class="w-full bg-[#fafafa]">
    <h1>Approver/~</h1>
    <p>My Workspace</p>
    <div class="flex gap-8  flex-wrap w-full">
      <WorkspaceItems text="Delayed Bulk Payment" icon="delayed.svg" />
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
export default {
  components: { WorkspaceItems },
};
</script>

<style lang="scss" scoped></style>
