<script setup>

</script>

<template>

    <div class="resultadoContainer">

        <table class="tableContainer">
            <tr>    
                <th >Nombre</th>
                <th >Apellido</th>
                <th >D.N.I.</th>
                <th >Historia Clínica</th>
            </tr>
            <tr>
                <td>Luciana</td>
                <td>Manetta</td>
                <td>36.603.951</td>
                <td>
                    <button>Info</button>
                </td>
            </tr>
        </table>


    </div>
    
</template>

<style scoped>

    .resultadoContainer{
        display: flex;
        justify-content: center;
        width:70%;
        height: 100px;
    }

    .tableContainer{
        display: flex;
        align-items: center;
        justify-content: center;
        table-layout: auto;
        margin-top:5%;
        width: 100%;
        


    }

    th{
        width:400px;
        border:1px double rgba(211, 239, 255, 0.904);
        background-color: azure ;
        font-weight: bold;
        box-shadow: 0px 0px 5px  black;
        border-radius: 1px 1px;
    }

    td{
        width: 400px;
        border:double 1px white;
        background-color: rgb(240, 252, 246);
        text-align: center;
        box-shadow: 0px 0px 5px  black;
        border-radius: 1px 1px;
        
    }


</style>