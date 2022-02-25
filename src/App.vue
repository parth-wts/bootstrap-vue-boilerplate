<template>
  <h1 class="mt-4"><b>bootstrap-vue-boilerplate</b></h1>
  <h3 class="mt-4"><b>Created By: Parth Popat</b></h3>
  <h5 class="blink_me mt-4 text-danger"><b>Thank you!</b></h5>
</template>

<script>


export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  
}
.blink_me {
  animation: blinker 1s linear infinite;
}

@keyframes blinker {
  50% {
    opacity: 0;
  }
}
</style>
