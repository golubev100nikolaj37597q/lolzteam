<template>
  <Header/>
  <Main/>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
export default {
  name: 'App',
  components: {
    Header,
    Main
  }
}
</script>

<style>
@import 'components/css/all.min.css'
</style>
