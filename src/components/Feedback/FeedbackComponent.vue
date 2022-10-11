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
                <CardFeedbackComponent v-for="card in getCardData()" :key="card.text1" 
                    :imgCard="card.img"
                    :text1Card="card.text1" 
                    :text2Card="card.text2" />
            </div>
        </div>

    </div>
</template>

<script>
import CardFeedbackComponent from './CardFeedbackComponent.vue';
import feedbackData from '@/data/feedback.json';
export default {
    name: 'FeedbackComponent',
    components: {
        CardFeedbackComponent,
    },

    methods: {
        getCardData() {
            return feedbackData;
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
        color: #c0c3d0;
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