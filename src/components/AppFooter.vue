<template>
    
    <footer>

        <section class="icon-section">
            <div class="container">

                <div class="icon-card">
                    <img class="icon-card_img" src="/img/buy-comics-digital-comics.png" alt="tablet con logo DC come schermata">
                    <p class="icon-card_description">Digital Comics</p>
                </div>

                <div class="icon-card">
                    <img class="icon-card_img" src="/img/buy-comics-digital-comics.png" alt="tablet con logo DC come schermata">
                    <p class="icon-card_description">Digital Comics</p>
                </div>

                <div class="icon-card">
                    <img class="icon-card_img" src="/img/buy-comics-digital-comics.png" alt="tablet con logo DC come schermata">
                    <p class="icon-card_description">Digital Comics</p>
                </div>

                <div class="icon-card">
                    <img class="icon-card_img" src="/img/buy-comics-digital-comics.png" alt="tablet con logo DC come schermata">
                    <p class="icon-card_description">Digital Comics</p>
                </div>

                <div class="icon-card">
                    <img class="icon-card_img" src="/img/buy-comics-digital-comics.png" alt="tablet con logo DC come schermata">
                    <p class="icon-card_description">Digital Comics</p>
                </div>

            </div>   
        </section>

        <section class="main-footer">
            <div class="container">
                <div class="row">
                    <div class="col-1">

                        <h4>Dc Comics</h4>
                        <ul>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                        </ul>

                        <h4>Dc Comics</h4>
                        <ul>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                        </ul>

                    </div>

                    <div class="col-1">

                        <h4>Dc Comics</h4>
                        <ul>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                        </ul>

                    </div>

                    <div class="col-1">

                        <h4>Dc Comics</h4>
                        <ul>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                            <li><a href="#">link</a></li>
                        </ul>

                    </div>
                </div>
            </div>
        </section>

        <section class="cta-footer">
            <div class="container">
                <div class="row cta-footer-row">

                    <div class="col">
                        <span class="button"><a href="#">Sign-up now!</a></span>
                    </div>

                    <div class="col">
                        <div class="row social-icon-box">
                            <p>Follow us</p>
                            <ul class="row social-icon-list">
                                <li><a href="#"><img src="/img/footer-facebook.png" alt=""></a></li>
                                <li><a href="#"><img src="/img/footer-twitter.png" alt=""></a></li>
                                <li><a href="#"><img src="/img/footer-youtube.png" alt=""></a></li>
                                <li><a href="#"><img src="/img/footer-pinterest.png" alt=""></a></li>
                                <li><a href="#"><img src="/img/footer-periscope.png" alt=""></a></li>
                            </ul>
                        </div>
                    </div>

                </div>
            </div>
        </section>

    </footer>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@use '../style/general.scss' as *;
@use '../style/partials/reset' as *;

.icon-section {
    height: 155px;
    background-color: #0282F9;
    
    .container{
        max-width: 1200px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        height: 100%;
    }

    .icon-card{
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        gap: 17px;
    }

        .icon-card_img{
            width: 43px;
            display: block;
        }

        .icon-card_description{
            color: white;
            text-transform: uppercase;
        }
}

.main-footer {
    padding: 45px 0;
    background-image: url('/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    color: white;

    .row{
        gap: 55px;
    }
}

.cta-footer {
    background-color: #303030;
    padding: 30px 0;

    .cta-footer-row{
        align-items: center;
        justify-content: space-between;
    }
    .social-icon-box{
        align-items: center;
        gap: 20px;

        p{
            font-size: 20px;
            font-weight: 700;
            color: #0282F9;
            text-transform: uppercase;
        }
    }

    .social-icon-list {
        gap: 20px;

        img{
        display: block;
        }
    }

    
}

</style>