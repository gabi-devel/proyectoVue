<script setup>
    import { ref } from 'vue';
    const contador = ref(0);

    function incrementar() {
        contador.value++;
    }
</script>

<template>
    <button @click="incrementar">{{contador}}</button>
    <h1></h1>
</template>

<style scope>

</style>