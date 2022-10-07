<template>
    <div>
        <CargoTransportComponent />
        <VehiclesComponent />
        <RoadTransportComponent/>
        <LogisticalProcedureComponent/>
        <ResultsComponent/>
        <FeedbackComponent/>

    </div>

</template>

<script>
import CargoTransportComponent from './CargoTransportComponent.vue';
import VehiclesComponent from './VehiclesComponent.vue';
import RoadTransportComponent from './RoadTransportComponent/RoadTransportComponent.vue';
import LogisticalProcedureComponent from './LogisticalProcedureComponent.vue';
import ResultsComponent from './ResultsComponent.vue';
import FeedbackComponent from './FeedbackComponent.vue';


export default {
    name: 'MainComponent',
    components: {
    CargoTransportComponent,
    VehiclesComponent,
    RoadTransportComponent,
    LogisticalProcedureComponent,
    ResultsComponent,
    FeedbackComponent
}

}
</script>

<style lang="scss" scoped>
main {
    max-width: 1000px;
}
</style>