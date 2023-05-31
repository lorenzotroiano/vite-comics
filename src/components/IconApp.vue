<script>


export default {
    name: "IconApp",

    data() {
        return {
            images: [
                {
                    text: "Digital Comics",
                    image: "buy-comics-digital-comics.png"
                },

                {
                    text: "Dc Merchendise",
                    image: "buy-comics-merchandise.png"
                },

                {
                    text: "Subscription",
                    image: "buy-comics-shop-locator.png"
                },

                {
                    text: "Comic Shop Locator",
                    image: "buy-comics-subscriptions.png"
                },

                {
                    text: "Dc Power Visa",
                    image: "buy-dc-power-visa.svg"
                }


            ]
        }

    }
}
</script>

<template>
    <div class="container">
        <section class="flex-icon">
            <div v-for="image in images" class="flex-items">
                <div>
                    <img :src="image.image" alt="">
                </div>
                <span>{{ image.text }}</span>
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