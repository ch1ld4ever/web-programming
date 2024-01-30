<template>
    <div class ="star-rating">
        <span v-for = "index in starLimit" key="index" class="star star-colored"></span>
    </div>


</template>

<script>
    export default {
        name: "StarRating",
        props: {
            rating: {
                type: Number,
                default: 0
            },
            starLimit: {
                type: Number,
                default : 5
            },
        }
    }


</script>

<style lang="scss" scoped>

</style>