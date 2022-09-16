<script setup>

</script>

<template>
    <div class="headerNav">
        <div class="logoContainer">
            <img class="logo" src="../assets/logo.svg" alt="Logo" />
        </div>

        <div class="headertitle">
            <a class="title" href="#">Registro Medico</a>
        </div>

        <div class="headerLogIn">
            <p>Cerrar sesión</p>
            <a href="#"><img class="userLogo" src="../assets/userIcon.svg" alt="LogIn"/></a>
        </div>

    </div>
</template>

<style scoped>
    .headerNav {
        display: flex;
        justify-content: space-around;
        width: 100%;
        height: 60px;
        background-color: #1aa4a8;
        
    }
    .logoContainer{
        display:flex;
        align-items: center;
        justify-content: center;
        width: 220px;
        min-width: 130px;
        
    }

    .logo{
        display: flex;
        width:60px;
        margin-left: -10px;
    }

    .headertitle{
        display:flex;
        margin:auto;
        align-items: center;
        justify-content: center;
        width: 80%;
        
    }

    .title{
        color:black;
        font-size: 1.3em;
    }

    .headerLogIn{
        display: flex;
        align-items: center;
        justify-content: space-evenly;
        margin:auto;
        width: 220px;
        min-width: 130px;
    }

    .userLogo{
        width: 46px;
    }
    
</style>