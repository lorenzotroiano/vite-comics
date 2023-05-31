<script>


export default {
    name: "IconApp"
}
</script>

<template>
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
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;

.flex-icon {
    display: flex;
    justify-content: space-around;

    padding: 40px;
    background-color: $colorePrimario;
}

.flex-items {
    display: flex;
    align-items: center;
}
</style>