<template>
  <div id="app">
    <Background />
    <Index />
  </div>
</template>

<script>
import Background from '@/components/Background'
import Index from '@/index/Index'

export default {
  name: 'App',
  components: {
    Background,
    Index
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
