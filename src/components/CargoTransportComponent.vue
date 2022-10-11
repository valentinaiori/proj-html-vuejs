<template>
    <div class="cargo">
        <div class="cargo-container">
            <div class="links-header">
                <div class="nexgen">
                    <h4 class="background">NEX</h4>
                    <h4>GEN</h4>
                </div>
                <nav>
                    <a href=""><strong>HOME</strong></a>
                    <a href=""><strong>ABOUT</strong></a>
                    <a href=""><strong>SERVICES</strong></a>
                    <a href=""><strong>PROCESS</strong></a>
                    <a href=""><strong>TESTIMONIALS</strong></a>
                    <i class="fa-regular fa-user"></i>
                    <button class="btn-green">GET IN TOUCH</button>
                </nav>
            </div>
            <div class="text-cargo-transport">
                <h5>LOGISTIC SERVICES</h5>
                <h1>CARGO TRANSPORT</h1>
                <p>Fractional or exclusive road cargo transportation to all regions with small, medium and large
                    vehicles.</p>
                <div class="action-button">
                    <button class="btn-green"><strong>GET IN TOUCH</strong></button>
                    <button class="btn-read"><strong>READ MORE</strong></button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CargoTransportComponent'

}
</script>

<style lang="scss" scoped>
.cargo {
    background-image: url(../assets/img/bg-9.jpg);
    padding-bottom: 100px;
    background-size: cover;
    background-position: center;
    padding-top: 30px;
}

.cargo-container {
    max-width: 1000px;
    height: 500px;

}

.links-header {
    display: flex;
    color: white;

    .nexgen {
        display: flex;
        padding-top: 8px;


        .background {
            border-radius: 40px 10px 10px 40px;
            width: 60px;
            text-align: end;
            color: #058283;
        }

        h4{
            color: #bdc0cc;
        }
    }

    nav a {
        color: white;
        text-decoration: none;
        padding-right: 30px;
        font-size: 0.9rem;
    }

    .fa-user {
        padding-right: 30px;

    }
}

.btn-green,
.btn-read {
    border: 1px solid #038384;
    padding: 10px 15px;
    background-color: #038384;
    border-radius: 5px;
    color: white;
    font-size: 0.8rem;
}

.text-cargo-transport {
    margin-top: 70px;
    width: 400px;
    margin-left: 0px;

    h5 {
        color: #038384;
        padding-bottom: 10px;
    }

    h1 {
        color: white;
        font-size: 3.0rem;
        padding-bottom: 10px;
    }

    p {
        color: #bcbdbd;
    }

    .btn-read {
        background-color: transparent;
        margin-left: 30px;
    }

    .action-button {
        padding-top: 20px;
    }
}
</style>