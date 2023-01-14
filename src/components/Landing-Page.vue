<template>
    <div class="landing-page">
      <Logo/>
      <Chamada/>
      <Blocos/>
      <SegundaChamada/>
      <Comentarios/>
    </div>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  import Logo from './Logo.vue'
  import Chamada from './Chamada.vue'
  import Blocos from './Blocos.vue'
  import SegundaChamada from './SegundaChamada.vue'
  import Comentarios from './Comentarios.vue'
  
  export default defineComponent({
    name: 'LandingPage',
    components: {
      Logo,
      Chamada,
      Blocos,
      SegundaChamada,
      Comentarios
    }
  });
  </script>
  
  <style >
  @import url(../reset.css);
  @import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Raleway&display=swap');
  .landing-page {
    background-color: #1C2230;
    min-height: 100vh;
    width: 100%;
  }
  </style>
  