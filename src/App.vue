<template>
    <div id="app" class="app">
        <router-view :key="$route.fullpath" />
    </div>
</template>

<script>
    export default {
        name: 'app'
    }
</script>
