<template>


    <div class="poster-col">
        <img :src="poster.thumb" alt="">
        <p>{{poster.series}}</p>
    </div>


</template>

<script>
export default {
    props:{
        poster: {
            type: Object,
            required: true
        }
    }

}
</script>

<style lang="scss" scoped>
@use '../style/general.scss' as *;


.poster-col{
    width: calc((100%/6) - (100px / 6));

    img{
        width: 100%;
        display: block;
        margin-bottom: 15px;
    }

    p{  
        font-size: 14px;
        text-transform: uppercase;
    }
}


</style>