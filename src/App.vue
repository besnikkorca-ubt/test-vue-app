<template>
  <RandomPrimeNumbers />
  <HomePage />
</template>

<script>
import RandomPrimeNumbers from '@/components/RandomPrimeNumbers.vue'
import HomePage from './components/HomePage.vue';

export default {
  name: 'App',
  components: {
    RandomPrimeNumbers,
    HomePage
  }
}
</script>

<style>

</style>
