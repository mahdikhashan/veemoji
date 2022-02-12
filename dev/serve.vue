<script>
import Vue from 'vue';
import Veemoji from '@/veemoji.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    Veemoji
  }
});
</script>

<template>
  <div id="app">
    <veemoji emoji="hundred"/>
  </div>
</template>
