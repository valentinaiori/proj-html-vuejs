<template>
    <CargoTransportComponent/>
  
</template>

<script>
import CargoTransportComponent from './CargoTransportComponent.vue';

export default {
    name: 'MainComponent',
    components: {
        CargoTransportComponent
    }

}
</script>

<style lang="scss" scoped>
    main{
        max-width: 1000px;
    }

</style>