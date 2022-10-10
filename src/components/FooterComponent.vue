<template>
    <footer>
        <div class="content">
            <div class="part-sx">
                <p>Enjoy the low price. We are tracking any intention of piracy.</p>
            </div>
            <div class="part-dx">
                <p>
                    <i class="fa-regular fa-copyright"></i> 2020 NEXGEN is Proudly Powered by 
                    <span class="green">Codings</span>.
                </p>
            </div>

        </div>

    </footer>
</template>

<script>
export default {
    name: 'FooterComponent'

}
</script>

<style lang="scss" scoped>
footer {
    height: 70px;
    background-color: black;
    display: flex;


    .content {
        width: 1000px;
        display: flex;

        p {
            color: white;
            font-size: 0.9rem;
            padding-top: 30px;
        }

        .green {
            color: #16928e;
        }

        .part-dx {
            margin-right: 0;
        }

        .part-sx {
            margin-left: 0;
        }
    }


}
</style>