<template>
    <div class="road-transport">
        <div class="container">
            <h5>ROAD TRANSPORT</h5>
            <h1>Main Service</h1>
            <div class="text-button">
                <p>With all of this expertise and capability comes an unrivalled commintment to customer service. We
                    will work hard to understand your needs in order to develop a productive, long-term partnership.</p>

                <button class="btn-see-all">SEE ALL</button>

            </div>

        </div>

    </div>
</template>

<script>
export default {
    name: 'RoadTransportComponent'

}
</script>

<style lang="scss" scoped>
.road-transport {
    height: 600px;
    background-color: #191c1e;
}

.container {

    max-width: 1000px;

    h1 {
        color: white;
        padding-top: 20px;
        padding-bottom: 20px;
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