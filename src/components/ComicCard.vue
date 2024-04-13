<script>
export default {
    name: 'ComicCard',
    props: ['image', 'title']
}
</script>

<template>
    <div class="card-comic">
        <img :src="image">
        <span>{{ title }}</span>
    </div>
</template>

<style scoped lang="scss">
img{
    width: 100%;
}

 .card-comic{
    
    width: calc(100% / 6) ;
    margin: 6px 0;
    padding: 10px;

    span{
        color: white;
        
    }
 }
</style>