<script setup>
import { ref }from 'vue'
const count = ref(0)
</script>

<template>
  <div>
    
    <h4> The current count is...</h4>
    <h1>{{count}}</h1>
    <button @click = "count++"> + </button>
    <button @click = "count--"> - </button>
    <svg id="10015.io" viewBox="0 0 480 480" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" >
      <path fill="#2528bb" d="M445,315Q418,390,348.5,424.5Q279,459,202,449.5Q125,440,88,374.5Q51,309,44,237.5Q37,166,94,126Q151,86,212,71Q273,56,342.5,75.5Q412,95,442,167.5Q472,240,445,315Z" />
    </svg>
  </div>
</template>

<style scoped>
button{
  border-radius: 20px;
  padding: 3px 12px;
  margin: 4px;
  border: none;
  font-size: medium;
  font-weight: bolder;
  background-color: rgb(249, 17, 17);
  color: white;
}
div{
  text-align: center;
}

</style>
