<template>
    <ul >
        <li v-for="prime in primeNumbers" v-bind:key="prime" >
            {{prime}}
        </li>
    </ul>
</template>

<script>
import listOfPrimes from 'prime-number/list';

export default {
    data() {
        return {
            primeNumbers: listOfPrimes
        }
    }
}
</script>

<style>
</style>