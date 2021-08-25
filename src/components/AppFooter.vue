<template>
  <div class="tw-bottom-0 tw-mt-20 tw-bg-gray-900 tw-shadow-2xl">
    <div class="tw-flex tw-flex-wrap tw-justify-between sm:tw-justify-start md:tw-justify-between tw-mb-10 tw-mx-2 xl:tw-mx-20">
      <div class="tw-mt-10 sm:tw-w-1/2 md:tw-w-1/3">
        <div class="tw-text-2xl sm:tw-text-3xl md:tw-text-4xl tw-text-green-400 tw-cursor-pointer hover:tw-text-green-500 tw-font-mono">
          Bexil's
        </div>
        <div class="tw-text-xs sm:tw-text-sm tw-mr-4 tw-mt-3 tw-tracking-widest tw-text-white tw-font-mono tw-font-thin">
          BEXIL COMPUTER & SOLUTION LIMITED is a duly registered limited liability company with registration number RC: 1299607. BEXIL COMPUTER & SOLUTION LIMITED has distinguished itself in the delivery of general ICT services, which includes Web design,  ICT  consultancy,  Training,  Computer  Networking, Computer repairs and supply, software development, graphic design and prints, security enhancement gadgets installations, CCTV cameras installations and lots more.
        </div>
      </div>
      <div class="tw-mt-2 sm:tw-mt-10 sm:tw-w-1/2 md:tw-w-1/3">
        <div class="tw-text-lg sm:tw-text-xl md:tw-text-2xl md:tw-ml-12 tw-text-green-400 tw-cursor-pointer hover:tw-text-green-500 tw-font-mono">
          Services
        </div>
        <div class="tw-text-xs sm:tw-text-sm tw-mt- tw-py-2 tw-tracking-widest md:tw-ml-12 tw-text-white tw-font-mono">
          Secure-NG
        </div>
        <q-separator class="md:tw-mx-10 tw-bg-gray-600" />
        <div class="tw-text-xs sm:tw-text-sm tw-mt- tw-py-2 tw-tracking-widest md:tw-ml-12 tw-text-white tw-font-mono">
          Transport Manifest
        </div>
        <q-separator class="md:tw-mx-10 tw-bg-gray-600" />
        <div class="tw-text-xs sm:tw-text-sm tw-mt- tw-py-2 tw-tracking-widest md:tw-ml-12 tw-text-white tw-font-mono">
          Data Optimisation
        </div>
        <q-separator class="md:tw-mx-10 tw-bg-gray-600" />
        <div class="tw-text-xs sm:tw-text-sm tw-mt- tw-py-2 tw-tracking-widest md:tw-ml-12 tw-text-white tw-font-mono">
          Software Development
        </div>
        <q-separator class="md:tw-mx-10 tw-bg-gray-600" />
        <div class="tw-text-xs sm:tw-text-sm tw-mt- tw-py-2 tw-tracking-widest md:tw-ml-12 tw-text-white tw-font-mono">
          Hardware Development
        </div>
        <q-separator class="md:tw-mx-10 tw-bg-gray-600" />
        <div class="tw-text-xs sm:tw-text-sm tw-mt- tw-py-2 tw-tracking-widest md:tw-ml-12 tw-text-white tw-font-mono">
          Facial Recognition System
        </div>
        <q-separator class="md:tw-mx-10 tw-bg-gray-600" />
        <div class="tw-text-xs sm:tw-text-sm tw-mt- tw-py-2 tw-tracking-widest md:tw-ml-12 tw-text-white tw-font-mono">
          CCTV Installation and management
        </div>
        <q-separator class="md:tw-mx-10 tw-bg-gray-600" />
      </div>            
      <div class="tw-mt-2 md:tw-mt-10 sm:tw-w-1/2 md:tw-w-1/3">
        <div class="tw-text-lg sm:tw-text-xl md:tw-text-2xl tw-ml-1 tw-text-green-400 tw-cursor-pointer hover:tw-text-green-500 tw-font-mono">
          Contact Us
        </div>
        <div class="tw-text-sm tw-mt-3 tw-text-white tw-font-mono tw-font-thin">
          <q-btn dense flat rounded icon="phone"></q-btn>  + 23480 2915 1377
          <q-separator class="tw-w-40" />
          <q-btn dense flat rounded icon="phone"></q-btn>  + 23490 2335 6064
          <q-separator class="tw-w-40" />
          <q-btn dense flat rounded icon="phone"></q-btn>  + 23480 6714 0502
          <q-separator class="tw-w-40" />
          <q-btn dense flat rounded icon="email"></q-btn><a class="tw-ml-2 tw-text-xs lg:tw-text-base" href="mailto:bexilcomputer@gmail.com">bexilcomputer@gmail.com</a>
        </div>
      </div>      
    </div>
    <q-separator class="tw-mx-6 md:tw-mx-20 tw-mb-10" />
    <div class="tw-flex tw-text-lg tw-text-white tw-justify-center">
      <q-btn flat dense size="xs" class="tw-mt-1" icon="copyright"></q-btn>
      <p class="tw-text-sm md:tw-text-base">{{ year }} Bexil. All rights reserved.</p>
    </div>
    <div class="tw-mt-4 md:tw-mt-7 tw-text-gray-50">.</div>
  </div>
</template>

<script>
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'AppFooter',
  setup() {
    const year = ref(new Date().getFullYear())
    return {
      year
    }
  }
})
</script>