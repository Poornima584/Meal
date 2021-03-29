<template>
  <div id="app">
    <!-- <h1 style="color:blue"> Meal </h1> -->
    <MealRecipies msg="Welcome to Meal App"/>
  </div>
</template>

<script>
import MealRecipies from './components/MealRecipies.vue'

export default {
  name: 'App',
  components: {
    MealRecipies
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:#2c3e50;
  margin-top: 60px;
}
</style>
