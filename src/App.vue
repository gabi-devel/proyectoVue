<script setup>
import HeaderNav from './components/HeaderNav.vue'
import Sidebar from './components/Sidebar.vue'
<<<<<<< HEAD
import Contador from './components/Contador.vue'
import ContadorData from './components/ContadorData.vue';
import Main from './components/Main.vue'
=======
import MainComponent from './components/MainComponent.vue'

>>>>>>> fe8df72354d368ba8053528d10c0ad2db2e0c8ec
</script>

<template>

  <HeaderNav />
<<<<<<< HEAD


  

  <div class="mainContainer">
    <Sidebar />
    <div class="btnContainer">
      
    </div>

    <Main />
=======
  <div class="side_main">
    <Sidebar />
    <MainComponent/>
>>>>>>> fe8df72354d368ba8053528d10c0ad2db2e0c8ec
  </div>

</template>

<style scoped>
<<<<<<< HEAD
  .mainContainer{
    display:flex;
  }
  .btnContainer{
    display:flex;
    height: 20px;
  }
=======

  .side_main{
    display:flex;
    flex-direction: row;
  }

>>>>>>> fe8df72354d368ba8053528d10c0ad2db2e0c8ec
</style>
