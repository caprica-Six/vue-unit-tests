<template>
     <div class="header">
         <ul>
             <li><router-link to="/hello-world">hello</router-link></li>
             <li><router-link to="/about">about</router-link></li>
         </ul>
     </div>
</template>

<script>
    export default {
        name: 'SectionHeader',
    }
</script>

<style>

    .header {
        background: #f1f1f1;
        padding: 20px;
        color: grey;
    }
    ul {
        list-style-type: none;
        padding: 0;
    }
    li {
        display: inline-block;
        margin: 0 10px;
    }
    a {
        color: #42b983;
    }
</style>
