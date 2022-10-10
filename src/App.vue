<template>
  <div id="app">
    <HeaderComponent/>
    <MainComponent/>
  </div>
</template>

<script>
import '@fortawesome/fontawesome-free/css/all.css';
import '@fortawesome/fontawesome-free/js/all.js';
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';

export default {
    name: "App",
    components: {
    HeaderComponent,
    MainComponent,
}
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat&family=Roboto&display=swap');
* {
  margin: 0 auto;
  padding: 0;
  box-sizing: border-box;
}

#app {
font-family: 'Roboto', sans-serif;;
}
</style>
