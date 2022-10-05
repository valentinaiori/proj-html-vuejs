<template>
    <header>
        <div class="bg-greydark">
            <div class="icon-dx">
                <i class="fa-solid fa-clock"></i> Oper Hours: Mon-Sat 9:00-18:00
            </div>
            <div class="icon-sx">
                <div>
                    <i class="fa-solid fa-phone"></i> +1 (305 1234-5678)
                    <i class="fa-solid fa-envelope"></i> <a href="">hello@example.com</a>
                    <i class="fa-brands fa-facebook"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-linkedin-in"></i>
                </div>
            </div>
        </div>
        <div class="cargo-container">
            <div class="links-header">
                <div>NEXGEN</div>
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
            <div class="cargo-transport">
                <h5>LOGISTIC SERVICES</h5>
                <h1>CARGO TRANSPORT</h1>
                <p>Fractional or exclusive road cargo transportation to all regions with small, medium and large
                    vehicles.</p>
                    <div class="btn-header">
                    <button class="btn-green"><strong>GET IN TOUCH</strong></button>
                    <button class="btn-read"><strong>READ MORE</strong></button>
                </div>
                    
                

            </div>
        </div>
    </header>

</template>

<script>
export default {
    name: 'HeaderComponent'

}
</script>

<style lang="scss" scoped>
header {
    color: #bcbdbd;
}

.bg-greydark {
    display: flex;
    align-items: center;
    background-color: #21333e;
    height: 50px;

    a {
        color: #bcbdbd;
        text-decoration: none;
    }

    .fa-twitter,
    .fa-linkedin-in{
        padding-right: 30px;

    }

    .fa-facebook {
        padding-right: 30px;
        padding-left: 30px;
    }

    .fa-phone,
    .fa-envelope {
        padding-right: 5px;
        padding-left: 30px;
    }

}

.cargo-container {
    background-image: url(../assets/img/bg-9.jpg);
    padding-bottom: 100px;
    width: 100%;
    background-size: cover;
    background-position: center;
    padding-top: 30px;
}

.links-header {
    display: flex;
    color: white;

    nav a {
        color: white;
        text-decoration: none;
        padding-right: 35px;
        font-size: 0.9rem;
    }

    .fa-user{
        padding-right: 30px;

    }
}

.btn-green, .btn-read {
    border: 1px solid #038384;
    padding: 10px 15px;
    background-color: #038384;
    border-radius: 5px;
    color: white;
    font-size: 0.8rem;
}

.cargo-transport{
    max-width: 400px;
    margin-left: 200px;
    margin-top: 70px;

    h5 {
    color: #038384;
    padding-bottom: 10px;
}

h1 {
    color: white;
    font-size: 3.0rem;
    padding-bottom: 10px;
}

p{
    color:#bcbdbd;
}

.btn-read{
    background-color: transparent;
    margin-left: 30px;


}

.btn-header{
    padding-top: 20px;
}
}


</style>