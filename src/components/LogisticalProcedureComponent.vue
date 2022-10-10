<template>
    <div class="container">
        <div class="text">
            <h5 class="subtitle">HOW IT WORKS IN PRACTISE</h5>
            <div class="title">
                <h1 class="background"><strong>Logistical</strong></h1>
                <h1><strong>Procedure</strong></h1>
            </div>

            <p class="paragraph">We work with innovative methodologies to ensure that the entire delivery procedd is
                done from start to finish as planned.</p>
        </div>
        <div class="logistical-procedure">
            <div class="steps">
                <h5 class="number">01</h5>
                <h3>Collection of information</h3>
                <p>Lorem ipsum dolor sit amet consectetur.</p>
            </div>
            <div class="steps">
                <h5 class="number">02</h5>
                <h3 class="procedure-2">Service Invoice Sending</h3>
                <p>Lorem ipsum dolor sit amet consectetur.</p>
            </div>
            <div class="steps">
                <h5 class="number">03</h5>
                <h3 class="procedure-3">Withdrawal of Cargo</h3>
                <p>Lorem ipsum dolor sit amet consectetur.</p>
            </div>
            <div class="steps">
                <h5 class="number">04</h5>
                <h3>Transport Customer Order</h3>
                <p>Lorem ipsum dolor sit amet consectetur.</p>
            </div>
            <div class="steps">
                <h5 class="number">05</h5>
                <h3>Successful Delivery</h3>
                <p>Lorem ipsum dolor sit amet consectetur.</p>
            </div>
        </div>

    </div>
</template>

<script>
export default {
    name: 'LogisticalProcedureComponent'

}
</script>

<style lang="scss" scoped>
.container {
    background-color: #e6ece8;
    padding-bottom: 100px;

    .text {
        text-align: center;
    }

    .subtitle {
        color: #038384;
        padding-top: 100px;
        padding-bottom: 20px;
    }

    .title {
        display: flex;
        width: 310px;

        .background {
            background-color: #cce3de;
            border: 1px solid #cce3de;
            color: #038384;
            width: 175px;
            height: 40px;
            margin-right: 5px;
        }
    }

    .paragraph {
        font-size: 0.8rem;
        color: #69696d;
        padding-top: 20px;
        width: 540px;
    }
}

.logistical-procedure {
    display: flex;
    text-align: center;
    padding-top: 70px;
    margin-right: 150px;
    margin-left: 150px;


    .steps {
        margin-right: 10px;
        margin-left: 10px;

        .procedure-2 {
            margin-right: 15px;
            margin-left: 15px;
        }

        .procedure-3 {
            margin-left: 30px;
            margin-right: 30px;
        }
    }

    .number {
        background-color: #daeced;
        border: 1px solid #daeced;
        color: #609d9f;
        border-radius: 50%;
        height: 30px;
        width: 32px;
        padding-top: 5px;
        margin-bottom: 20px;
    }

    h3 {
        margin-bottom: 20px;
        margin-right: 10px;
        margin-left: 10px;
    }

    p {
        color: #69696d;
        font-size: 0.8rem;
    }

}
</style>