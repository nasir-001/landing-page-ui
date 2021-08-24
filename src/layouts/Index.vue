<template>
  <top-bar />
  <overview />
</template>

<script>
import { defineComponent } from 'vue';
import TopBar from '../components/TopBar.vue';
import Overview from '../components/Overview';

export default defineComponent({
  name: 'Index',
  components: {
    TopBar,
    Overview
  }
})
</script>