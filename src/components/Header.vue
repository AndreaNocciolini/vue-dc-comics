<template>
    <div class="header">
        <div>
            <img :src="imageLink" alt="">
        </div>
       
        <ul>
            <li><a href="">CHARACTERS</a></li>
            <li><a class="active" href="">COMICS</a></li>
            <li><a href="">MOVIES</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">GAMES</a></li>
            <li><a href="">COLLECTIBLES</a></li>
            <li><a href="">VIDEOS</a></li>
            <li><a href="">FANS</a></li>
            <li><a href="">NEWS</a></li>
            <li><a href="">SHOP</a></li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'Header',
    data (){
        return{
            imageLink: require("../assets/img/dc-logo.png")
        }
    }
    
}
</script>

<style lang="scss" scoped>
    .header {
        width: 80%;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    ul {
        display: flex;
        font-size: 0.6em;
        list-style-type: none;
        li a{
            display: block;
            padding: 2em 1em;
            text-decoration: none;
            color: black;
            &:hover,
            &:active,
            &.active {
                color: #005ebd;
                border-bottom: 3px solid #005ebd;
            }
        }
    }
</style>