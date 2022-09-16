<script setup>

</script>

<template>
    <div class="sidebarContainer">
        <form action="#" method="post">
            <label class="label_paciente">DNI paciente: </label>
            <input class="inputBuscador" type="text" name="buscador" id="buscadorSideBar">

            <button class="btnBuscador" type="submit">Buscar</button>
            <button class="btnBuscador" type="submit">Borrar</button>
            <label class="label_paciente">Acciones </label>
            <button class="btnBuscador2" type="submit">Agregar Paciente</button>
        </form>


    </div>
</template>

<style scoped>
.label_paciente {
    margin-top: 20px;
    color: #ffffff80;
}
.sidebarContainer {
    /* display: flex;
    flex-direction: column;
    justify-content: center; */
    width: 220px;
    height: 100vh;
    background-color: #212529;
    padding: 18px 10px;
}
/* 
@media (max-width:768px){
    .sidebarContainer{
        display:none;
    }
} */

.inputBuscador{
    width:60%;
    margin: auto;
    margin-top: 20px;
    font-size: smaller;
}

.btnBuscador{
    width: 40%;
    margin: auto;
    margin: 10px 2px;
    display: inline-block;
    font-size: 0.7em;
}
.btnBuscador2{
    margin: auto;
    margin: 10px 2px;
    display: block;
    font-size: 0.7em;
}


</style>