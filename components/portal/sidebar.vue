<script setup>
const links = [
  {
    label: 'HomePage',
    icon: 'i-heroicons-chart-bar',
    to: '/'
  },
  {
    label: 'Dashboard',
    icon: 'i-heroicons-home',
    to: '/portal'
  },
  {
    label: 'Settings',
    icon: 'i-heroicons-chart-bar',
    to: '/portal/settings'
  }
]
</script>

<template>
  <UVerticalNavigation :links="links"/>
</template>

