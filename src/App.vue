<template>


  <StepOne msg=""/>
  <StepTwo msg=""/>
  <StepThree msg=""/>
  <StepFour msg=""/>
  
</template>

<script>
import StepOne from './components/StepOne.vue'
import StepTwo from './components/StepTwo.vue'
import StepThree from './components/StepThree.vue'
import StepFour from './components/StepFour.vue'


export default {
  name: 'App',
  components: {
    StepOne,
    StepTwo,
    StepThree, 
    StepFour
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
