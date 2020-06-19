<template>
  <div id="app">
    <router-view/>
    <!-- <h2>111111111</h2> -->
    <main-tab-bar/>
  </div>
</template>
<script>
import MainTabBar from 'components/content/maintarbar/MainTarBar'
export default {
  name:'app',
  components:{
    MainTabBar
  }
}
</script>
<style>
@import "./assets/css/base.css";
</style>
