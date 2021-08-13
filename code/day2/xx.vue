<template>
  
<div >
  <input v-model="name" />
  <h1>天气不错</h1>
  <p @click="handleChild"> {{name}} </p> 
</div>



</template>