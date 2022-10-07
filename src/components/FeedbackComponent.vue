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
        </div>
    </div>
</template>

<script>
export default {
    name: 'FeedbackComponent'

}
</script>

<style lang="scss" scoped>
.container {
    height: 600px;
    background-color: #121117;

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

    p{
        font-size: 0.8rem;
        color: #69696d;
        padding-top: 20px;
        width: 573px;
        text-align: center;
    }
}
</style>