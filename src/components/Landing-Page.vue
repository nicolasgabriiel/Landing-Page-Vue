<template>
    <div class="landing-page">
      <Logo/>
      <Chamada/>
      <Blocos/>
    </div>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  import Logo from './Logo.vue'
  import Chamada from './Chamada.vue'
  import Blocos from './Blocos.vue'
  
  export default defineComponent({
    name: 'LandingPage',
    components: {
      Logo,
      Chamada,
      Blocos
    }
  });
  </script>
  
  <style >
  @import url(../reset.css);
  .landing-page {
    background-color: #1C2230;
    min-height: 100vh;
    width: 100%;
  }
  </style>
  