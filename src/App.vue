<script setup>
import HeaderNav from './components/HeaderNav.vue'
import Sidebar from './components/Sidebar.vue'
import Contador from './components/Contador.vue'
import ContadorData from './components/ContadorData.vue';
import Main from './components/Main.vue'
</script>

<template>

  <HeaderNav />


  

  <div class="mainContainer">
    <Sidebar />
    <div class="btnContainer">
      
    </div>

    <Main />
  </div>

</template>

<style scoped>
  .mainContainer{
    display:flex;
  }
  .btnContainer{
    display:flex;
    height: 20px;
  }
</style>
