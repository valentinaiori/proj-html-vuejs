<template>
    <div class="road-transport">
        <div class="container">
            <h5>ROAD TRANSPORT</h5>
            <div class="title">
                <h1>Main</h1>
                <h1 class="background">Service</h1>
            </div>

            <div class="text-button">
                <p>With all of this expertise and capability comes an unrivalled commintment to customer service. We
                    will work hard to understand your needs in order to develop a productive, long-term partnership.</p>
                <button class="btn-see-all">SEE ALL</button>
            </div>
        </div>
        <CardRoadTransportComponent />
    </div>
</template>

<script>
import CardRoadTransportComponent from './CardRoadTransportComponent.vue'

export default {
    name: 'RoadTransportComponent',
    components: {
        CardRoadTransportComponent,
    }

}
</script>

<style lang="scss" scoped>
.road-transport {
    height: 400px;
    background-color: #191c1e;
}

.container {

    max-width: 1000px;

    .title {
        display: flex;
        width: 140px;
        color: white;
        padding-top: 20px;
        padding-bottom: 20px;
        margin-left: 0;

        .background {
            background-color: #0e272d;
            border: 1px solid #0e272d;
            width: 199px;
            height: 42px;
            margin-left: 10px;
            padding-left: 6px;
            padding-right: 6px;
        }
    }

    h5 {
        color: #038384;
        padding-top: 100px;
    }

    p {
        color: #bcbdbd;
        font-size: 0.8rem;
    }

    .btn-see-all {

        background-color: transparent;
        width: 150px;
        margin-left: 30px;
        border: 1px solid #038384;
        padding: 10px 15px;
        border-radius: 5px;
        color: white;
        font-size: 0.8rem;
    }

    .text-button {
        display: flex;

    }

}
</style>