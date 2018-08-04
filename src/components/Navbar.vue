<template>
    <div>
        <ul>
            <li v-for="nav in navlink">{{nav}}</li>
        </ul>
    </div>
</template>

<script>
export default {
    data() {
        return {
            navlink: ['About Me', 'Education', 'Certificates', 'Projects', 'Contacts']
        }
    }
}
</script>

<style scoped>
    div {
        display: flex;
        justify-content: center;
        margin: 0;
        padding: 0%;
        align-items: flex-start;
    }
    
    div > ul {
        list-style-type: none;
        display: flex;
        background-color: blanchedalmond;
        justify-content: space-between;
        margin: 0;
    }

    li {
        flex: 1;
        background-color: aqua;
        
    }
</style>

