<script setup>
import HomePageVue from './components/HomePageVue/HomePageVue.vue'

const arr = [1,2,3,4,5,6]
const obj = {
  kivi: 'Super kivi',
  banana: 'Super banana',
  tomato: 'Super tomato'
}
</script>

<template>
    <HomePageVue />
    <div :key="num" v-for="num in arr">
      {{ num }}
    </div>

    <div :key="fruit" v-for="( fruit, key ) in obj">{{key}}: {{ fruit }}</div>

    <div :key="letter" v-for="letter in 'Hello'">{{ letter }}</div>
</template>
