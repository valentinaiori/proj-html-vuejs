<template>
    <div class="container">
        <div class="first-part">
            <div class="information">
                <h1>NEXGEN</h1>
                <p class="subtitle">A Functional HTML Template for Corporate & Business.</p>
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
                <button class="touch">GET IN TOUCH</button>
            </div>
            <div class="container-links">
                <div class="links">
                    <div class="content">
                        <h3>About</h3>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">The Company</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Institutional</a>
                        </div>

                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Social & Events</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Innovation</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Enviroment</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Technology</a>
                        </div>
                    </div>

                </div>
                <div class="links">
                    <div class="content">
                        <h3>Transport</h3>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Industrialized</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Chemicals</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Packaged Liquids</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Construction</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Laminated Wood</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">And Others</a>
                        </div>
                    </div>

                </div>
                <div class="links">
                    <div class="content">
                        <h3>Support</h3>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Responsibility</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Terms of Use</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">About Cookies</a>
                        </div>

                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Privacy Policy</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Accessibility</a>
                        </div>
                        <div class="link">
                            <i class="fa-solid fa-angle-right"></i>
                            <a href="">Information</a>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterComponent'

}
</script>

<style lang="scss" scoped>
.container {
    background-color: beige;
    color: white;
    background-color: #111117;
    padding-top: 100px;
    padding-bottom: 150px;
}

.first-part {
    width: 1000px;
    display: flex;

    .information {
        margin-right: 50px;
    }

    .subtitle {
        font-size: 1rem;
        width: 220px;
        padding-bottom: 40px;
        padding-top: 30px;
        color: #c0c3d0;
    }

    .fa-phone,
    .fa-envelope,
    .fa-location-dot {
        color: #c0c3d0;
    }

    .info {
        padding-bottom: 30px;

        a {
            color: #c0c3d0;
            text-decoration: none;
        }

        .text {
            padding-left: 30px;
            margin-top: -20px;
        }

    }

    .touch {
        border: 1px solid #038384;
        padding: 10px 15px;
        background-color: #111117;
        border-radius: 5px;
        color: white;
        font-size: 0.8rem;
    }

}

.container-links {
    display: flex;
    flex-direction: row;
    margin-top: 30px;
}

.links {
    flex-direction: column;
    width: 220px;
    height: 300px;
    background-color: #19191f;
    border: 1px solid #19191f;
    border-radius: 10px;
    margin-right: 20px;

    .content {
        padding-left: 30px;
        padding-top: 30px;

        h3 {
            padding-bottom: 20px;
        }
    }

    .link {
        padding-bottom: 10px;
        color: #c0c3d0;
    }

    a {
        color: white;
        font-size: 1rem;
        text-decoration-line: none;
        color: #c0c3d0;
    }

    .fa-angle-right {
        padding-right: 10px;
        padding-bottom: 0px
    }
}

.second-part {
    height: 10px;
    background-color: black;
}
</style>