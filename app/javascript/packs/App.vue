<template>
  <div id="App">
    <app-server-status></app-server-status>
    <p>{{ message }}</p>
  </div>
</template>

<script>
  export default {
    data: function () {
      return {
        message: "Hello Vue!"
      }
    }
  }
</script>

 