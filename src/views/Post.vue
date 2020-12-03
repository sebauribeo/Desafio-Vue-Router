<template>
    <div>
        <!-- CONTENIDO PARA LA VISTA PRINCIPAL O PADRE DEL POST -->
        <div>
            <router-link :to="{name: 'Articulos'}"></router-link> 
        </div>
        <router-view></router-view>
    </div>
</template>

<script>
    export default {
        name: 'Post'
    }
</script>

<style>

</style>