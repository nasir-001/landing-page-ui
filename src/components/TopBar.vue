<template>
  <div class="tw-flex tw-justify-between tw-mx-5 sm:tw-mx-10 md:tw-mx-28 tw-mt-5 sm:tw-mt-12 md:tw-mt-16">
    <div class="flex tw-justify-start tw--mt-4">
      <div class="tw-text-xl tw-mt-6 sm:tw-mt-2 sm:tw-text-2xl md:tw-text-4xl tw-font-serif tw-cursor-pointer tw-uppercase text-green">
        <router-link to="/">
          bexil
        </router-link>
      </div>
    </div>
    <div class="tw-flex tw-justify-start md:tw--mt-6">
      <div class="bg-green tw-rounded md:tw-h-12 tw-h-10 tw-w-10 md:tw-w-12"></div>
      <div class="bg-green tw-rounded md:tw-h-12 tw-h-10 tw-w-10 md:tw-w-12 tw-mt-3 md:tw-mt-4 tw-text-gray-800 tw-font-serif tw--ml-5 md:tw--ml-4 tw-text-base md:tw-text-2xl">B</div>
    </div>
  </div>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'TopBar'
})
</script>