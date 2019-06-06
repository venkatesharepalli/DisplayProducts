<template>
  <div id="app"> 
    <MainNavigation />
   
  </div>  
</template>

<script>
import MainNavigation from "./components/MainNavigation.vue";
//import TestpaketHeader from "./components/TestpaketHeader.vue";
//import TestpaketContent from "./components/TestpaketContent.vue";

export default {
  name: "app",
  components: {
    MainNavigation,
   // TestpaketHeader,
   // TestpaketContent
  },
  data() {
    return {
      testPaketInfo: [
        {size: 1, weight: "2-3", testpaket: 10},
        {size: 2, weight: "3-4", testpaket: 20},
        {size: 3, weight: "4-7", testpaket: 30},
        {size: 4, weight: "7-10", testpaket: 40},
        {size: 5, weight: "10-12", testpaket: 50}       
      ]
    }   
  }
};
</script>

<style scoped>
@import './assets/css/App.scss';
</style>
