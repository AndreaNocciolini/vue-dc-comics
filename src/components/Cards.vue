<template>
    <div class="container-card">
        <img :src="srcImage" alt="">
        <h5>{{title}}</h5>
    </div>
</template>

<script>
export default {
    name: "Cards",
    props: [
        "srcImage", "title"
    ]
}
</script>

<style lang="scss" scoped>
    .container-card {
        width: calc(100% / 7);
        img{
            width: 150px;
            height: 180px;
        }
    }
</style>