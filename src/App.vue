<template>
  <div id="app">
    <e-videos></e-videos>
  </div>
</template>

<script>
import eVideos from '@/components/video'
export default {
  name: 'App',
  components: { eVideos }
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
