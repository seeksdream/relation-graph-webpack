<template>
    <div id="app">
        <h1>Hello, Vue 2 with Webpack!</h1>
        <Simple />
    </div>
</template>

<script>
import Simple from "./demos/Simple.vue";

export default {
    name: 'App',
    components: {Simple},
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
