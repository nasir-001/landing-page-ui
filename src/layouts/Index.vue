<template>
  <top-bar />
  <overview />
  <app-footer />
</template>

<script>
import { defineComponent } from 'vue';
import TopBar from '../components/TopBar.vue';
import Overview from '../components/Overview';
import AppFooter from '../components/AppFooter';

export default defineComponent({
  name: 'Index',
  components: {
    TopBar,
    Overview,
    AppFooter
  }
})
</script>