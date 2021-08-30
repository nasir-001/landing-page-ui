<template>
  <div :class="[$q.screen.lt.sm ? 'q-pa-sm' : 'q-pa-xl']">
    <q-video
      :ratio="16/9"
      src="/vid/sample.mp4"
    />
  </div>
</template>

<script>
import { defineComponent } from 'vue';
import { useQuasar } from 'quasar';

export default defineComponent({
  name: 'Projects',

  setup() {
    const $q = useQuasar()
  }
})
</script>