<template>
    <header>
        <h1>{{welcome}}</h1>
        <h2>{{myName}}</h2>
    </header>
    
</template>

<script>
export default {
    data(){
        return {
            welcome: 'Welcome to my portfolio page',
            myName: 'I am Ady Jalil!'
        }
    }
}
</script>

<style scoped>
    header {
        text-align: center;
        background-color: blueviolet;
        align-items: center;
        width: 70%;
        margin: auto;
        margin-top: 0;
        margin-bottom: 0;
    }

    h1 {
        margin-top: 0;
        
    }
    h2 {
        margin-bottom: 0;
    }
    
</style>


