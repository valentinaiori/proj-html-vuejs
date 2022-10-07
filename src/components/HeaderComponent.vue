<template>
    <header>
        <div class="bg-greydark">
            <div class="icon-dx">
                <i class="fa-solid fa-clock"></i> Open Hours: Mon-Sat 9:00-18:00
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
    .fa-linkedin-in {
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

</style>