<template>
  <div>
    <h1 class="underlined">Calculator</h1>
    <Calculator />
  </div>
</template>

<script>
import Calculator from "./components/Calculator.vue";
// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/master/active-rfcs/0040-script-setup.md
export default {
  components: {
    Calculator,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
html {
  background-color: #222;
  color: white;
}
.underlined {
  text-decoration: underline;
  margin-bottom: 50px;
}
</style>
