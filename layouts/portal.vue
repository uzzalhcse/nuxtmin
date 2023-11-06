<template>
  <div>
<!--    <h1>Portal Layout</h1>-->
    <div class="">
      <div class="sidebar">
        <PortalSidebar />
      </div>
      <div class="main-area p-4 sm:ml-64">
        <PortalNavbar />
        <slot />
      </div>
    </div>

  </div>
</template>
<script setup>
</script>
