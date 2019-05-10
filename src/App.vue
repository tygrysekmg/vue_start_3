
<template>
  <div id="app"> 
  <HelloWorld msg="Zaczynamy pisać w Vue.js!"/>  
  <HelloAgain /> 

<GrzegorzList>
  <li>This is slot for php</li>
  <li>This is slot for python</li>
    <li>This is slot for perl</li>

</GrzegorzList>

  </div>
  </template>
  <script>
  import HelloWorld from './components/HelloWorld.vue';
  import HelloAgain from './components/HelloAgain.vue';
  
  import GrzegorzList from './components/GrzegorzList.vue';
  export default 
  { 
  name: 'app',  components: {    HelloWorld, HelloAgain,   GrzegorzList }
  }
  </script>
  <style>
  #app {
  font-family:
  sans-serif;
  text-align: left;
  color: #2c3e50; 

  margin-top: 60px;
  }
  #app li {
    margin-right: 90px;
  }
  </style>