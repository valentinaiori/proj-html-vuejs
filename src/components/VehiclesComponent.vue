<template>
    <div class="vehicles">
        <div class="vehicles-container">
            <div class="text-vehicles">
                <h5>WHO WE ARE</h5>
                <div class="title">
                    <h1 class="background"><i class="fa-regular fa-gem"></i>Excellence</h1>
                    <h1>in Transport</h1>
                </div>

                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                    Aspernatur, pariatur non. </p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit quas perspiciatis veniam.
                    Autem architecto nam voluptate labore optio tempore numquam?
                    Eveniet voluptates quos eligendi fugit voluptatibus enim tempore culpa at! </p>
                <p class="paragraph-line">Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit quas perspiciatis veniam.
                    Autem architecto nam voluptate labore optio tempore numquam? </p>
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
                            <p class="type"><strong>Light</strong></p>
                            <p class="max-weight">Max Weigth 1200 Kg</p>
                        </div>
                    </div>
                    <div class="bar">
                        <hr>
                    </div>
                    <div class="card">
                        <img src="../assets/img/truck-1.png" alt="Medium">
                        <div>
                            <p class="type"><strong>Medium</strong></p>
                            <p class="max-weight">Max Weigth 6000 Kg</p>
                        </div>
                    </div>
                    <div class="bar">
                        <hr>
                    </div>
                    <div class="card">
                        <img src="../assets/img/truck-1.png" alt="Heavy">
                        <div>
                            <p class="type"><strong>Heavy</strong></p>
                            <p class="max-weight">Max Weigth 24000 Kg</p>
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
h5 {
    color: #038384;
}

.vehicles {
    max-width: 1000px;
    margin-bottom: 100px;

    .vehicles-container {
        display: flex;
    }

    .title {
        display: flex;
        margin-left: 0;
        width: 380px;

        .background {
            background-color: #cce3de;
            border: 1px solid #cce3de;
            color: #038384;
            width: 204px;
            height: 39px;
            padding-left: 5px;
            padding-right: 3px;
        }
    }

}

.text-vehicles {
    font-size: 0.7rem;
    color: #6f7875;

    h1 {
        font-size: 2.0rem;
        color: black;
    }

    h5 {
        margin-top: 50px;
        margin-bottom: 20px;
    }

    p,
    ul {
        padding-top: 20px;
    }

    ul {
        padding-left: 20px;
    }

    li {
        padding-bottom: 15px;
    }

    .fa-gem {
        padding-right: 10px;
    }

    .paragraph-line{

    }

}

.types-vehicles {
    width: 370px;

    h3 {
        margin-top: 60px;
        margin-left: 63px;
    }

    img {
        width: 60px;
        height: 40px;
        text-align: center;
        background-color: #daeced;
    }

    p {
        font-size: 0.7rem;
    }

    .text {
        padding-top: 12px;
    }

}

.bar {
    padding-right: 3px;
    padding-left: 59px;
    width: 249px;
    padding-top: 10px;
}

.card {
    display: flex;
    margin-top: 20px;
    width: 200px;
    margin-left: 57px;

    .type {
        font-size: 0.9rem;
        padding-bottom: 2px;
    }

    .max-weight {
        color: #6f7875;
    }
}

.certifications {
    h3 {
        margin-bottom: 10px;
        margin-top: 35px;
        font-size: 1.0rem;
    }

    img {
        width: 90px;
        height: 78px;
        background-color: white;
    }

    .img-certification {
        margin-left: 58px;
    }
}
</style>