<template>

  <header>

    <div>
      <h1><img src="../assets/logo.svg"></h1>
    </div>

    <div>
      <nav>
        <a>Features</a>
        <a>Team</a>
        <a>Sign In</a>
      </nav>
    </div>

  </header>

</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Logo-Header',

})
</script>

<style scoped>
header{
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 4% 10%;
}

nav > a {
  font-size: 18px;
  color: white;
  margin-left: 50px;
  font-family: 'Raleway'
}

nav > a:hover {
  font-weight: bold;
  text-decoration: underline;
  cursor: pointer;
}
</style>

