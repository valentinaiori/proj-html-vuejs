<template>
  <div id="app">
    <HeaderComponent/>
    <MainComponent/>
    <FooterComponent/>
  </div>
</template>

<script>
import '@fortawesome/fontawesome-free/css/all.css';
import '@fortawesome/fontawesome-free/js/all.js';
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

export default {
    name: "App",
    components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
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
