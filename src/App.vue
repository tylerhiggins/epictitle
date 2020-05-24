<template>
  <div id="app">
    <construction></construction>
    <foot></foot>
  </div>
</template>

<script>
  import construction from './components/Construction.vue'
  import foot from './components/Foot.vue'
  export default {
    components: {
      construction,
      foot
    }
  }
</script>


<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

</style>
