<template>
    <div>
      <!-- <NuxtWelcome /> -->
      <h1>hellow </h1>
      <button @click="increment()">Increment</button>
      <h2>{{ count }}</h2>
      <button @click="decrement()">Decrement</button>
    </div>
  </template>
  
  
  <script setup>
  
  const count = ref(0)
  
  const increment = ()=>{
    count.value++
  }
  const decrement = ()=>{
    count.value--
  }
  
  </script>
  