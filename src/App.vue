<template>
  <div>
    <Logo/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Logo from './components/Logo.vue'

export default defineComponent({
  name: 'App',
  components: {
    Logo
  }
});
</script>

<style >
@import url(./reset.css);
#app {
  background-color: #1C2230;
  min-height: 100vh;
  width: 100%;
}
</style>
