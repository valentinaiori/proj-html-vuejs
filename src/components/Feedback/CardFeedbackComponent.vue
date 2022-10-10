<template>
    <div class="card">
        <img :src="imgCard">
        <p class="text">{{text1Card}}</p>
        <p>{{text2Card}}</p>
        <div>
            <i class="fa-solid fa-quote-right"></i>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CardFeedbackComponent',
    props: {
        imgCard: String,
        text1Card: String,
        text2Card: String
    }
}
</script>

<style lang="scss" scoped>
.card {
    padding-top: 30px;
    width: calc(100% / 3);
    margin-right: 33px;
    height: 210px;
    background-color: #19191f;
    border: 1px solid #19191f;
    border-radius: 10px;

    p {
        width: 200px;
        font-size: 0.8rem;
        padding-bottom: 10px;
        color: #69696d;
    }

    .fa-quote-right {
    color: grey;
    font-size: 1.3rem;
    display: flex;
    margin-right: 0;
    padding-right: 20px;
    padding-bottom: 10px;
    }
}


</style>