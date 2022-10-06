<template>
    <div>
        <CargoTransportComponent />
        <VehiclesComponent />
        <RoadTransportComponent/>

    </div>

</template>

<script>
import CargoTransportComponent from './CargoTransportComponent.vue';
import VehiclesComponent from './VehiclesComponent.vue';
import RoadTransportComponent from './RoadTransportComponent.vue';


export default {
    name: 'MainComponent',
    components: {
    CargoTransportComponent,
    VehiclesComponent,
    RoadTransportComponent
}

}
</script>

<style lang="scss" scoped>
main {
    max-width: 1000px;
}
</style>