<template>
  <div>

  </div>
</template>

<script setup lang="ts">
definePageMeta({
  validate: async (route) => {
    // Check if the id is made up of digits
    return /^\d+$/.test(route.params.id)
  }
})
</script>

<style lang="scss" scoped>

</style>
