<script>


export default {
    name: "HeaderApp"
}
</script>

<template>
    <header>
        <nav>
            <div>
                <img src="../assets/images/dc-logo.png" alt="logo">
            </div>

            <div>
                <ul>
                    <li><a href="#">Link N</a></li>
                    <li><a href="#">Link N</a></li>
                    <li><a href="#">Link N</a></li>
                    <li><a href="#">Link N</a></li>
                    <li><a href="#">Link N</a></li>
                    <li><a href="#">Link N</a></li>
                    <li><a href="#">Link N</a></li>
                    <li><a href="#">Link N</a></li>
                    <li><a href="#">Link N</a></li>
                    <li><a href="#">Link N</a></li>
                </ul>
            </div>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;

nav {
    display: flex;
    align-items: center;
    justify-content: space-between;

    div>ul {
        display: flex;
        justify-content: flex-end;


        list-style: none;

        li a {
            &:hover {
                color: $colorePrimario;
                border-bottom: 3px solid $colorePrimario;

            }
        }


    }
}
</style>