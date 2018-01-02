<template>
  <div id="app">
    <left-nav></left-nav>
    <router-view/>
  </div>
</template>

<script>
import leftNav from './components/leftNav'
export default {
  name: 'app',
  components:{
    leftNav,
  }
}
</script>

<style>

</style>
