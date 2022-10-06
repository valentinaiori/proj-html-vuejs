<template>
    <div class="vehicles">
        <div class="vehicles-container">
            <div class="text-vehicles">
                <h1>Excellence in Transport</h1>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                    Aspernatur, pariatur non. </p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Amet dolores odit ullam voluptatum, tempore voluptatem laboriosam sunt totam doloribus </p>
                <p>Sed maurius nulla, tempor eu est vel, dapibus hendrerit maurius curabitur dictum phaetra.</p>

                <ul>
                    <li>Lorem ipsum dolor sit amet</li>
                    <li>Consectetur adipisicing elit</li>
                    <li>Integer molestie lorem at massa</li>
                    <li>Facilisis in pretium nils aliquet</li>
                    <li> Dapibus hendrerit maurius curabitur</li>
                </ul>

            </div>
            <div class="types-vehicles">
                <h3>Vehicles Types</h3>
                <div>
                    <div class="card">
                        <img src="../assets/img/truck-1.png" alt="Light">
                    <div class="text">
                        <p><strong>Light</strong></p>
                        <p>Max Weigth 1200 kg</p>
                    </div>
                </div>
                <div class="card">
                    <img src="../assets/img/truck-1.png" alt="Medium">
                    <div>
                        <p><strong>Medium</strong></p>
                        <p>Max Weigth 6000 kg</p>
                    </div>
                </div>
                <div class="card">
                    <img src="../assets/img/truck-1.png" alt="Heavy">
                    <div>
                        <p><strong>Heavy</strong></p>
                        <p>Max Weigth 24000 kg</p>
                    </div>
                    
                </div>
                <div class="certifications">

                    <h3>Certifications</h3>
                    <div class="img-certification">
                        <img src="../assets/img/certificate.png" alt="Certificate">
                    <img src="../assets/img/certificate.png" alt="Certificate">
                    </div>
                    
                </div>
            
            </div>
            </div>
            
        </div>
    </div>
</template>

<script>
export default {
    name: 'VehiclesComponent'

}
</script>

<style lang="scss" scoped>
.vehicles {
    max-width: 1000px;
    height: 600px;

    .vehicles-container {
        display: flex;
    }

}

.text-vehicles {

    h1 {
        margin-top: 50px;
    }

    p, ul{
        padding-top: 20px;
    }

    ul{
        padding-left: 20px;
    }

}

.types-vehicles{

    h3{
        margin-top: 60px;
        margin-left: 75px;
    }
    img{
        width: 15%;
        text-align: center;
    }

    p{
        font-size: 0.7rem;
    }

    .text{
        padding-top: 12px;
    }
}

.card{
    display: flex;
    margin-top: 20px;
}

.certifications{
    h3{
        margin-bottom: 20px;
    }

    img{
        width: 15%;
        padding-right: 10px;
    }

    .img-certification{
        padding-left: 108px;
    }
    
}

</style>