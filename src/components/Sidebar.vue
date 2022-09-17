<script setup>

</script>

<template>
    <div class="sidebarContainer">
        <form class="formBuscador" action="#" method="post">
            <label class="label_paciente">DNI paciente: </label>
            <input class="inputBuscador" type="text" name="buscador" id="buscadorSideBar">
            <button class="btnBuscador" type="submit">Buscar</button>
            <button class="btnAgregar" type="submit">Agregar Paciente</button>
        </form>


    </div>
</template>

<style scoped>

.sidebarContainer {

    display: flex;
    justify-content: center;
    width: 250px;
    height: 90vh;
    background-color: #212529;
    padding: 18px 10px;
}

/* 
@media (max-width:768px){
    .sidebarContainer{
        display:none;
    }
} */

.formBuscador{
    display:flex;
    flex-direction: column;
    align-items: center;
}

.label_paciente {
    display:flex;
    color: #ffffff80;
}

.inputBuscador{
    display: flex;
    width:80%;      
    margin-top: 10px;
    font-size: medium;
}



.btnBuscador{
    display: flex;
    width: 40%; 
    margin: 20px 2px;
    display: inline-block;
    font-size: 1em;
}
.btnAgregar{
    display: flex;
    display: block;
    font-size: 1em;
}


</style>