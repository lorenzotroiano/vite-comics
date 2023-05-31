<script>


export default {
    name: "IconApp"
}
</script>

<template>
    <div class="container">
        <section class="flex-icon">
            <div class="flex-items">
                <div>
                    <img src="../assets/images/buy-comics-digital-comics.png" alt="">
                </div>
                <span>Ciao</span>
            </div>

            <div class="flex-items">
                <div>
                    <img src="../assets/images/buy-comics-merchandise.png" alt="">
                </div>
                <span>Ciao</span>
            </div>

            <div class="flex-items">
                <div>
                    <img src="../assets/images/buy-comics-shop-locator.png" alt="">
                </div>
                <span>Ciao</span>
            </div>

            <div class="flex-items">
                <div>
                    <img src="../assets/images/buy-comics-subscriptions.png" alt="">
                </div>
                <span>Ciao</span>
            </div>

            <div class="flex-items">
                <div>
                    <img src="../assets/images/buy-dc-power-visa.svg" alt="">
                </div>
                <span>Ciao</span>
            </div>
        </section>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;


.container {
    background-color: $colorePrimario;
}

.flex-icon {
    display: flex;
    justify-content: space-around;

    width: 90%;
    margin: 0 auto;
    padding: 40px;
    background-color: $colorePrimario;
}

.flex-items {
    display: flex;
    align-items: center;

    img {
        margin-right: 10px;
    }
}
</style>