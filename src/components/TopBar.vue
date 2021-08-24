<template>
  <div class="tw-flex tw-justify-between tw-mx-4 sm:tw-mx-16 md:tw-mx-24 tw-mt-16">
    <div class="flex tw-justify-start tw--mt-4">
      <div class="tw-mt-5 sm:tw-mt-0">
        <!-- <img class="tw-w-10 tw-h-10 sm:tw-w-14 sm:tw-h-14 tw-object-cover"  src="/img/logo.jpg" alt=""> -->
      </div>
      <div class="tw-text-xl tw-mt-6 sm:tw-mt-2 sm:tw-text-2xl tw-cursor-pointer tw-uppercase tw-text-white hover:tw-text-gray-300">
        <router-link to="/">
          bexils tech
        </router-link>
      </div>
    </div>
    <div class="md:tw-flex tw-hidden tw-justify-evenly tw--mt-2">
      
    </div>
  </div>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'TopBar'
})
</script>