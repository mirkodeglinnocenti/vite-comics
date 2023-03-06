<template>
    
    <footer>

        <section class="icon-section">
            <div class="container">

                <div class="icon-card">
                    <img class="icon-card_img" src="/img/buy-comics-digital-comics.png" alt="tablet con logo DC come schermata">
                    <p class="icon-card_description">Digital Comics</p>
                </div>

                <div class="icon-card">
                    <img class="icon-card_img" src="/img/buy-comics-merchandise.png" alt="tablet con logo DC come schermata">
                    <p class="icon-card_description">Dc merchandise</p>
                </div>

                <div class="icon-card">
                    <img class="icon-card_img" src="/img/buy-comics-subscriptions.png" alt="tablet con logo DC come schermata">
                    <p class="icon-card_description">subscription</p>
                </div>

                <div class="icon-card">
                    <img class="icon-card_img" src="/img/buy-comics-shop-locator.png" alt="tablet con logo DC come schermata">
                    <p class="icon-card_description">comic shop location</p>
                </div>

                <div class="icon-card">
                    <img class="icon-card_img" src="/img/buy-dc-power-visa.svg" alt="tablet con logo DC come schermata">
                    <p class="icon-card_description">dc power visa</p>
                </div>

            </div>   
        </section>

        <section class="main-footer">

            

            <div class="container">
                <div class="row">
                    <div class="col-1">

                        <h4>Dc Comics</h4>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>

                        <h4>Shop</h4>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>

                    </div>

                    <div class="col-1">

                        <h4>Dc</h4>
                        <ul>
                            <li><a href="#">Terms Of Use</a></li>
                            <li><a href="#">Privacy policy(New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contacs Us</a></li>
                        </ul>

                    </div>

                    <div class="col-1">

                        <h4>Sites</h4>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>

                    </div>
                    
                    <div class="dc-logo-footer">
                        <img src="/img/dc-logo-bg.png" alt="">
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
    position: relative;

    .row{
        gap: 55px;
    }
}

.dc-logo-footer{
    position: absolute;
    right: 200px;
    width: 300px;
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