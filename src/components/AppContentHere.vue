<script>
export default {
    name: 'AppContentHere'
}
</script>

<template>
    <div class="jumbo-container">
        <img src="../assets/img/jumbotron.jpg" alt="jumbotron">
    </div>
</template>

<style scoped  lang="scss">
    .jumbo-container{
        height: 500px;
        overflow: hidden;
        
    }

    img{
        object-fit: cover;
        margin: 0 auto;
        display: flex;
        padding-top: 130px;
    }
</style>