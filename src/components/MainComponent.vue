<template>
    <div>
        <CargoTransportComponent />
        <VehiclesComponent />
        <RoadTransportComponent/>
        <LogisticalProcedureComponent/>
        <ResultsComponent/>
        <FeedbackComponent/>
        <SendMessageComponent/>
        <LinksComponent/>

    </div>

</template>

<script>
import CargoTransportComponent from './CargoTransportComponent.vue';
import VehiclesComponent from './VehiclesComponent.vue';
import RoadTransportComponent from './RoadTransport/RoadTransportComponent.vue';
import LogisticalProcedureComponent from './LogisticalProcedureComponent.vue';
import ResultsComponent from './ResultsComponent.vue';
import FeedbackComponent from './Feedback/FeedbackComponent.vue';
import SendMessageComponent from './SendMessageComponent.vue';
import LinksComponent from './LinksComponent.vue';


export default {
    name: 'MainComponent',
    components: {
    CargoTransportComponent,
    VehiclesComponent,
    RoadTransportComponent,
    LogisticalProcedureComponent,
    ResultsComponent,
    FeedbackComponent,
    SendMessageComponent,
    LinksComponent
}

}
</script>

<style lang="scss" scoped>
main {
    max-width: 1000px;
}
</style>