<template>
  <div class="container">
    <div>
        <h5>WHAT WE ARE DOING</h5>
        <h1>Results in Number</h1>
    </div>
    <div class="data">
        <div>
            <p class="number"><strong>128</strong></p>
            <p><strong>Certifications</strong></p>
        </div>
        <div>
            <p class="number"><strong>230</strong></p>
            <p><strong>Employees</strong></p>
        </div>
        <div>
            <p class="number"><strong>517</strong></p>
            <p><strong>Customers</strong></p>
        </div>
        <div>
            <p class="number"><strong>94</strong></p>
            <p><strong>Countries Served</strong></p>
        </div>
    </div>

  </div>
</template>

<script>
export default {
    name: 'ResultsComponent'

}
</script>

<style lang="scss" scoped>
    .container{
        background-image: url(../assets/img/bg-10.jpg);
        padding-bottom: 150px;
        background-size: cover;
        background-position: center;

        h5{
            color: #038384;
            padding-top: 100px;
            padding-bottom: 20px;
            text-align: center;
        }

        h1{
            color: white;
            text-align: center;
        }
    }

    .data{
        display: flex;
        padding-top: 100px;
        width: 900px;

        .number{
            color:#038384;
            font-size: 2rem;
            text-align: center;
        }

        p{
            color: white;
            padding-top: 10px;
        }
    }

</style>