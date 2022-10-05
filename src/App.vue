<template>
  <div id="app">
    <HeaderComponent/>
  </div>
</template>

<script>
import '@fortawesome/fontawesome-free/css/all.css';
import '@fortawesome/fontawesome-free/js/all.js';
import HeaderComponent from './components/HeaderComponent.vue';

export default {
    name: "App",
    components: { HeaderComponent }
}
</script>

<style lang="scss">
* {
  margin: 0 auto;
  padding: 0;
  box-sizing: border-box;
}
</style>
