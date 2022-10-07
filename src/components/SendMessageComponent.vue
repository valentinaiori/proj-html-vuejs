<template>
    <div class="container">
        <div class="send-message">
            <h5>SEND A MESSAGE</h5>
            <div class="title">
                <h1>Get in</h1>
                <h1 class="background">Touch</h1>
            </div>
            <p>We will respond to your message as soon as possible.</p>
            <div>
                <div class="form">
                    <input type="text" value="Name">
                    <input type="tel" value="Phone">
                </div>
                <div class="form">
                    <input type="email" value="Email">
                    <input type="text" value="More Info">
                </div>

                <textarea name="Message"></textarea>

                <div>
                    <button class="send">SEND</button>
                </div>

            </div>
        </div>

        <div class="example">
            <h3><strong>Example Inc.</strong></h3>
            <p>Lorem ipsum dolor sit amet, consectetur adibiscing elit.</p>
            <p>Praesent diam lacus, dapibus sed imperdiet consectur.</p>
            <div class="info">
                <i class="fa-solid fa-phone"></i>
                <p class="text">+1 (305 1234-5678)</p>
            </div>
            <div class="info">
                <i class="fa-solid fa-envelope"></i>
                <p class="text"><a href="">hello@example.com</a></p>
            </div>
            <div class="info">
                <i class="fa-solid fa-location-dot"></i>
                <p class="text">Main Avenue, 978</p>
            </div>
            <button class="view">VIEW MAP</button>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.container {
    width: 1000px;
    display: flex;
    padding-bottom: 100px;
}

.send-message {

    h5 {
        color: #038384;
        padding-top: 100px;
        padding-bottom: 20px;
    }

    .title {
        display: flex;
        margin: 0;
        width: 200px;

        .background {
            color: #038384;
            background-color: #cce3de;
            border: 1px solid #cce3de;
            width: 100px;
            padding-left: 5px
        }
    }

    p {
        font-size: 0.8rem;
        color: #69696d;
        padding-top: 20px;
    }

    .form {
        display: flex;

        input {
            width: 220px;
            height: 40px;
            margin: 0;
            background-color: #ececec;
            border: 1px solid #ececec;
            margin-top: 10px;
            margin-right: 10px;
            border-radius: 4px;
        }
    }

    textarea {
            height: 140px;
            width: 450px;
            margin-top: 20px;
            background-color: #ececec;
            border: 1px solid #ececec;
            border-radius: 4px;
        }

    .send {
        border: 1px solid #038384;
        padding: 10px 15px;
        background-color: #038384;
        border-radius: 5px;
        color: white;
        font-size: 0.8rem;
        margin-top: 10px;
    }
}

.example {
    padding-top: 100px;

    p {
        margin-top: 20px;
        margin-bottom: 20px;
        width: 300px;
        margin-left: 0;
    }

    .fa-phone,
    .fa-envelope,
    .fa-location-dot {

        background-color: #daeced;
        border: 1px solid #daeced;
        color: #609d9f;
        border-radius: 50%;
        height: 17px;
        width: 31px;
        padding-top: 5px;
        padding-bottom: 5px;
    }

    .info {
        display: flex;

        .text {
            padding-left: 10px;
            margin-top: 5px;
        }
    }

    .view {
        border: 1px solid #038384;
        padding: 10px 15px;
        background-color: white;
        border-radius: 5px;
        color: #038384;
        font-size: 0.8rem;
    }
}
</style>