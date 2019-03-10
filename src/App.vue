<template>
  <div id="app">
    <leftNav></leftNav>
    <!-- <router-view></router-view> -->
  </div>
</template>

<script>
import leftNav from '@/components/common/leftNav'
export default {
  name: 'App',
  components:{
    leftNav
  }
}
</script>
<style>
</style>
