<template>
  <div id="app">
    <Calculator/>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue' // 1.

export default { // 2.
  name: 'app',
  components: {
    Calculator
  }
}
</script>

<style>
#app {
  /* .. Styling .. */
}
</style>