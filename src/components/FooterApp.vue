<script>


export default {
    name: "FooterApp"
}
</script>

<template>
    <section class="flex-footer">
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

.flex-footer {
    display: flex;
    justify-content: space-between;


    background-color: $colorePrimario;
}

.flex-items {
    display: flex;
    align-items: center;
}
</style>