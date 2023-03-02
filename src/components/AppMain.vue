<template>

    <main>
        <section>
            <div class="container">
                <p class="text-example"> Scrivi qua </p>
                
            </div>

            <section class="poster-section">
                <div class="container">
                    <div class="poster-row">

                        <ComicsCard v-for="(posterItem, i) in posters" :key="i" :poster="posterItem"/>

                    </div>
                </div>
            </section>
            
            
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
                    "thumb": "/img/superman.png",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/superman.png",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/superman.png",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/superman.png",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/superman.png",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "/img/superman.png",
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

    .poster-row{
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
    }
    .poster-col{
        width: calc((100%/6) - (100px / 6));
    }

}

</style>