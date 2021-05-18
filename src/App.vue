<template>
  <div>
      <div class="row">
    <div class="col-md-4"> 
       <AccountInfo/></div>
      <div class="col-md-4"> 
      <Contactinfo/></div>
      <div class="col-md-4"> 
      <MicsInfo/></div>
      </div>  
  </div>
</template>

<script>
import AccountInfo from "./components/AccountInfo"
import Contactinfo from './components/Contactinfo.vue'
import MicsInfo from './components/MicsInfo.vue';
export default {
  name: "App",
  components: {
    AccountInfo,
    Contactinfo,
    MicsInfo
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
