<template>
  <div class="page">
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: 'Page'
  }
</script>

<style scoped lang="scss">
  @import "@/style/variables";

  .page {
    height: $A4-height-px;
    overflow: hidden;
    page-break-after: always;
    position: relative;
    widows: inherit;
  }
</style>
