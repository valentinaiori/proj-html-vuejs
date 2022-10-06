<template>
    <div>
        <CargoTransportComponent />
        <VehiclesComponent />

    </div>

</template>

<script>
import CargoTransportComponent from './CargoTransportComponent.vue';
import VehiclesComponent from './VehiclesComponent.vue';


export default {
    name: 'MainComponent',
    components: {
        CargoTransportComponent,
        VehiclesComponent
    }

}
</script>

<style lang="scss" scoped>
main {
    max-width: 1000px;
}
</style>