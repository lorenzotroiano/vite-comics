<script>


export default {
    name: "HeaderApp",
    data() {
        return {
            links: [
                {
                    text: "Characters",
                    link: "#"
                },

                {
                    text: "Comics",
                    link: "#"
                },

                {
                    text: "Movies",
                    link: "#"
                },

                {
                    text: "Tv",
                    link: "#"
                },

                {
                    text: "Games",
                    link: "#"
                },

                {
                    text: "Collectibles",
                    link: "#"
                },

                {
                    text: "Videos",
                    link: "#"
                },

                {
                    text: "Fans",
                    link: "#"
                },

                {
                    text: "News",
                    link: "#"
                },

                {
                    text: "Shop",
                    link: "#"
                }
            ]
        }

    }
}
</script>

<template>
    <div class="container">
        <header>
            <nav>
                <div>
                    <img src="../assets/images/dc-logo.png" alt="logo">
                </div>

                <div>
                    <ul v-for="link in links">
                        <li><a :href="links.link">{{ link.text }}</a></li>
                    </ul>
                </div>
            </nav>
        </header>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;

.container {
    background-color: white;
}

header {
    width: 90%;
    margin: 0 auto;
    padding: 10px;
}

nav {
    display: flex;
    align-items: center;
    justify-content: space-between;

    div {
        display: flex;
        justify-content: flex-end;

        li a {
            &:hover {
                color: $colorePrimario;
                border-bottom: 3px solid $colorePrimario;

            }
        }


    }
}
</style>