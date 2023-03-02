<template>

    <main>
        <section class="main-hero">
            <div class="container">
                <span class="button-primary"><a href="#">Current series</a></span>
            </div>
        </section>

        <section class="poster-section">
            <div class="container">
                <div class="poster-row">

                    <ComicsCard v-for="(posterItem, i) in posters" :key="i" :poster="posterItem"/>

                </div>
            </div>

            <div class="button-box">
                <span class="button-primary"><a href="#">Load More</a></span>
            </div>

        </section>
            
    </main>

</template>


<script>
import ComicsCard from './ComicsCard.vue';

export default {
    components: {
        ComicsCard,
    },
    data () {
        return{
            posters: [
                {
                    "thumb": "/img/superman.png",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/american-vampire.png",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/acquaman.png",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "/img/batgirl.png",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/batman.png",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/batman.png",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/batman-superman.png",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/batman-superman-annual.png",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/batman-joker.png",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/three-jokers.png",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/harley-quinn.png",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/catwoman.png",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
            ]

        }
    }
}
</script>

<style lang="scss" scoped>
@use '../style/general.scss' as *;
@use '../style/partials/reset' as *;

section {
    background-color: #1C1C1C;
    color: white;

    .container {
        display: flex;
        justify-content: start;
        align-items: center;
        height: 100%;
    }

    .text-example{
        font-size: 36px;
    }
}

.poster-section {
    padding-top: 80px;
    padding-bottom: 30px;

    .poster-row{
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
    }
    .poster-col{
        width: calc((100%/6) - (100px / 6));
    }
    .button-box{
        display: flex;
        justify-content: center;
    }

    .button-primary{
        font-size: 14px;
        padding: 10px 50px;
        line-height: 5px;
        margin: 0;
    }
    
}

.button-primary{
        font-size: 22px;
        font-weight: 800;
        background-color: #0282f9;
        padding: 10px 50px;
        line-height: 30px;
        margin-top: 400px;
    }
.main-hero {
    background-image: url('/img/jumbotron.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-color: #1C1C1C;
    height: 400px;
}

</style>