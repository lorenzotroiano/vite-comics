<script>


export default {
    name: "FooterApp",

    data() {
        return {
            icons: [
                {
                    icon: "footer-facebook.png"
                },

                {

                    icon: "footer-periscope.png"
                },

                {

                    icon: "footer-pinterest.png"
                },

                {

                    icon: "footer-twitter.png"
                },

                {

                    icon: "footer-youtube.png"
                }


            ]
        }

    }
}
</script>

<template>
    <footer>
        <div class="container-top">
            <div class="flex-principale">
                <div class="flex-footer">
                    <section>
                        <h3>DC Comics</h3>
                        <ul>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                        </ul>
                    </section>

                    <section>
                        <h3>DC</h3>
                        <ul>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                        </ul>
                    </section>

                    <section>
                        <h3>Sites</h3>
                        <ul>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>
                            <li>Ciao</li>

                        </ul>
                    </section>

                    <section>
                        <h3>Shop</h3>
                        <ul>
                            <li>Ciao</li>
                            <li>Ciao</li>

                        </ul>
                    </section>
                </div>
                <img src="../assets/images/dc-logo-bg.png" alt="">
            </div>
        </div>


        <div class="container-bottom">
            <section class="flex-social">
                <button>
                    <a href="#">Clicca qui</a>
                </button>


                <div>
                    <span>Follow Us</span>
                    <img v-for="icon in icons" :src="icon.icon" alt="">
                </div>
            </section>
        </div>


    </footer>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;

.container-top {
    background-image: url(../assets/images/footer-bg.jpg);
    background-repeat: no-repeat;
}

.flex-principale {
    display: flex;
    justify-content: space-between;
    width: 90%;
    margin: 0 auto;

    padding: 25px;

    img {
        width: 400px;
        margin-right: 40px;
    }
}

.flex-footer {
    display: flex;
    justify-content: flex-start;
    flex-wrap: wrap;
    align-items: flex-start;
    width: calc(100% / 5);
    gap: 40px;

    color: white;

}

footer {
    background-image: url(../assets/images/footer-bg.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;

    .container-bottom {
        background-color: #303030;
    }

    .flex-social {
        display: flex;
        justify-content: space-between;
        align-items: center;

        width: 90%;
        margin: 0 auto;


        padding: 15px;
        background-color: #303030;

        button {

            border: 2px solid $colorePrimario;
            background-color: #303030;
            padding: 10px;

            a {
                color: white;
            }
        }

        div {
            display: flex;
            align-items: center;


            span {
                color: $colorePrimario;
                font-size: 20px;
                font-weight: bold;

            }

            img {
                width: 30px;
                margin: 0 15px;
            }
        }

    }
}
</style>