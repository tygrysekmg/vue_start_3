<template>
 <p class="hello-again"> This is Grzegorz master vue.js  component.
 <button v-on:click="incrementUp">Add One</button>
 <br> 
 <span>Current value of the counter: {{ counter }}</span> </p>
 </template>


<script>
export default
 { name: 'HelloAgain', data() {  
 return {         counter: 0     } },
 methods: {     incrementUp: function() 
 {         this.counter++     }
 }
 }
 </script>


<style scoped>
p {

 font-size: 16px; text-align: letf;
 color: tomato;
 }

 p .hello-again {
       text-align: left;

 }
 
 button {  
 display: block;    margin: left;    background: tomato;    color: white;    border: none;    padding: 5px 10px;    font-size: 16px;    border-radius: 4px;    cursor: pointer;
 }
 </style>