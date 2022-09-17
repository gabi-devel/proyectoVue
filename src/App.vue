<script setup>
import HeaderNav from './components/HeaderNav.vue'
import Sidebar from './components/Sidebar.vue'
import MainComponent from './components/MainComponent.vue';

</script>

<template>

  <HeaderNav />

  <div class="side_main">
    <Sidebar />
    <MainComponent />
  </div>

</template>

<style scoped>
.side_main {
  display: flex;
  flex-direction: row;
}
</style>
