<script setup>
    
</script>

<template>
    <div class="headerNav">
        <div class="logoContainer">
            <img class="logo" src="../assets/logo.svg" alt="Logo" />
        </div>
    </div>
</template>

<style scoped>
    .headerNav {
        display: flex;
        width: 100%;
        height: 60px;
        background-color: #1aa4a8;
    }

    .logoContainer{
        display:flex;
        align-items: center;
        justify-content: center;
        width: 130px;
        /*border: solid 1px red;*/
    }

    .logo{
        display: flex;
        width:60px;
        margin-left: -10px;
    }
</style>