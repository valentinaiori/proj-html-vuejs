<template>
    <div class="container">
        <div class="feedback">
            <h5>CUSTOMER TESTIMONIALS</h5>
            <div class="title">
                <h1>Trusted</h1>
                <h1 class="background">Feedback</h1>
            </div>
            <p> We work intensively in search of ideals that can add up in the lives of our customers.
                This is what moves us and we are grateful for the recognition.
            </p>

            <div class="card-container">
                <CardFeedbackComponent v-for="card in getCardData()" :key="card.text1" :imgCard="card.img"
                    :text1Card="card.text1" :text2Card="card.text2" />
            </div>
        </div>

    </div>
</template>

<script>
import CardFeedbackComponent from './CardFeedbackComponent.vue';
export default {
    name: 'FeedbackComponent',
    components: {
        CardFeedbackComponent,
    },

    methods: {
        getCardData() {
            const cardData = [
                {
                    'img': 'logo-1.png',
                    'text1': 'Praesent volutpat justo sit amet elementum malesuada. Praesent sagittis augue justo, in accumsam orci rhoncus at pellentesque.',
                    'text2': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
                },
                {
                    'img': 'logo-2.png',
                    'text1': 'Praesent volutpat justo sit amet elementum malesuada. Praesent sagittis augue justo, in accumsam orci rhoncus at pellentesque.',
                    'text2': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
                },
                {
                    'img': 'logo-3.png',
                    'text1': 'Praesent volutpat justo sit amet elementum malesuada. Praesent sagittis augue justo, in accumsam orci rhoncus at pellentesque.',
                    'text2': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
                }
            ]
            return cardData;
        }
    }

}
</script>

<style lang="scss" scoped>
.container {
    padding-bottom: 100px;
    background-color: #121117;
    color: white;

    .feedback {
        width: 1000px;

    }

    h5 {
        color: #038384;
        padding-top: 100px;
        padding-bottom: 20px;
        text-align: center;
    }

    .title {
        color: white;
        display: flex;
        width: 270px;

        .background {
            background-color: #0e272d;
            border: 1px solid #0e272d;
            width: 207px;
            height: 40px;
            padding-left: 10px;
            margin-left: 8px
        }
    }

    p {
        font-size: 0.8rem;
        color: #69696d;
        padding-top: 20px;
        width: 573px;
        text-align: center;
        padding-bottom: 80px;
    }
}

.card-container {
    display: flex;
}
</style>