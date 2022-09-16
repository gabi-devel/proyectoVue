<script>

    export default{
        data(){
            return{
                contador:0
            }
        },
        methods:{
            incrementar(){
                this.contador++;
            }
        }
        
    }

</script>

<template>

    <button @click="incrementar">{{contador}}</button>

</template>

<style scope>

</style>