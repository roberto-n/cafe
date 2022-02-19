<template>
  <div id="app">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app{
   width: 100%;
   height: 100%;
   padding:0;
   margin:0;
}
body{
   width: 100%;
   height: 100%;
   padding:0;
   margin:0;
}

</style>
