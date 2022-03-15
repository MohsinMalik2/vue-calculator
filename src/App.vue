<template>
<HeadingComponent/>
  <CalculatorComponent msg="Welcome to Your Vue.js App"/>
</template>

<script>
import CalculatorComponent from './components/CalculatorComponent.vue'
import HeadingComponent from './components/Heading.vue'

export default {
  name: 'App',
  components: {
    CalculatorComponent,
    HeadingComponent
  }
}
</script>

<style>
#app {
  position: absolute;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  left:35%;
  top:20%;
}
</style>
