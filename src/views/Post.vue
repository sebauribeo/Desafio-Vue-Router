<template>
    <div>
        <div>
            <router-link tag="button" to="{name: 'Articulos'}"></router-link> 
            <router-view></router-view>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Post',   
           
    }
</script>

<style>

</style>