<template>
  <div class="grzegorzlist">
    <h2>Grzegorz List</h2>
    <ul>
      <slot><li>All done!</li></slot>
    </ul>
  </div>
</template>
<script>
  export default {
    name: 'GrzegorzList'
  }
</script>