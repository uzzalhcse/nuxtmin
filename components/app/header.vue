<template>
  <div>
    <nav class="">
      <div class="mx-auto px-2 sm:px-6 lg:px-8">
        <div class="relative flex h-16 items-center justify-between">
          <div class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start">
            <div class="flex flex-shrink-0 items-center">
              <img class="h-8 w-auto" src="@/assets/img/logo.png" alt="Your Company">
            </div>
            <div class="flex flex-1 bg-white rounded-[16px] ml-2">
              <div class="flex flex-1 justify-between space-x-4">
                <div class="p-2">
                  <p class="text-[12px] text-gray-900 font-bold">13/p Mymenshing Lane, Dhaka</p>
                  <p class="text-[12px] text-gray-400">Your Address</p>
                </div>
                <UFormGroup size="md" class="flex items-center">
                  <UInput input-class="bg-gray-100 border-gray-100 rounded-[10px]" id="search" type="search" placeholder="Search" icon="i-heroicons-magnifying-glass" />
                </UFormGroup>
                <button type="button" class="inline-flex items-center px-4 py-2 my-[3px] text-sm font-medium text-gray-900 bg-gray-100 rounded-[16px] hover:bg-gray-200">
                  <UIcon class="mr-2 h-5 w-5 text-green-500 font-bold" name="i-heroicons-shopping-bag" />
                  <span class="font-bold text-green-500">02</span>
                </button>
              </div>
            </div>
          </div>
          <div class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
            <!-- Profile dropdown -->
            <div class="relative ml-3">
              <div>
                <nuxt-link to="/portal" class="relative flex rounded-full bg-gray-800 text-sm focus:outline-none focus:ring-2 focus:ring-white focus:ring-offset-2 focus:ring-offset-gray-800" id="user-menu-button" aria-expanded="false" aria-haspopup="true">
                  <span class="absolute -inset-1.5"></span>
                  <span class="sr-only">Open user menu</span>
                  <img class="h-8 w-8 rounded-full" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
                </nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>

  </div>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>

<style lang="scss" scoped>

</style>
