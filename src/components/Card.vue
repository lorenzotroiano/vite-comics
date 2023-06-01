<script>


export default {
    name: "Card",

    props: {
        details: Object
    }


}
</script>

<template>
    <div class="card">
        <img :src="details.thumb" alt="">
        <h5>{{ details.series }}</h5>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;





.card {

    width: calc(90% / 8);
    margin-top: 20px;

    img {
        width: 130px;
        height: 130px;
    }


    h5 {
        color: white;

    }
}
</style>