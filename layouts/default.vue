
<template>
  <div>
    <the-header @sidenavToggle="displaySidenav = !displaySidenav"/>

    <the-side-nav :show="displaySidenav" @close="displaySidenav = false"/>
    
    <nuxt/>
  </div>
</template>

<script>
/* eslint-disabled */ 
import TheHeader from '@/components/Navigation/TheHeader'
import TheSideNav from '@/components/Navigation/TheSidenav'

export default {
  components: {
    TheHeader,
    TheSideNav
  },
  data(){
    return{
      displaySidenav : false
    }
  }
}
</script>

<style>
  html{
    font-family: 'Open Sans', sans-serif;
  }
  body{
    margin: 0;
  }
</style>
