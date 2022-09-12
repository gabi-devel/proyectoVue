<script setup>

</script>

<template>
    <div class="sidebarContainer">

        <form action="#" method="post">
            <input class="inputBuscador" type="text" name="buscador" id="buscadorSideBar">

            <button class="btnBuscador" type="submit">Buscar</button>
        </form>


    </div>
</template>

<style scoped>
.sidebarContainer {
    display: flex;
    justify-content: center;
    width: 130px;
    height: 100vh;
    background-color: #212529;
}
/* 
@media (max-width:768px){
    .sidebarContainer{
        display:none;
    }
} */

.inputBuscador{
    display: flex;
    width:60%;
    margin: auto;
    margin-top: 20px;

    font-size: smaller;
}

.btnBuscador{
    display: flex;
    width: 40%;
    margin: auto;
    margin-top: 10px;

    font-size: 0.7em;
}


</style>