<template>
    
    <header>
        <div class="container">
            <div class="row justify-content-between">

                <div>
                    <img class="logo-img" src="/img/dc-logo.png" alt="logo DC Comics">
                </div>

                <ul class="menu-list">
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">comics</a></li>
                    <li><a href="#">movies</a></li>
                    <li><a href="#">tv</a></li>
                    <li><a href="#">games</a></li>
                    <li><a href="#">collectibles</a></li>
                    <li><a href="#">videos</a></li>
                    <li><a href="#">fans</a></li>
                    <li><a href="#">news</a></li>
                    <li><a href="#">shop</a></li>


                </ul>

            </div>
        </div>      
    </header>

</template>


<script>
    export default {

    }
</script>


<style lang="scss" scoped>
@use '../style/partials/reset' as *;
@use '../style/general.scss' as *;


.logo-img{
    max-width: 80px;
    display: block;
}

.menu-list{
    display: flex;
    flex-wrap: wrap;

    li{
        margin: 0 17px;
        text-transform: uppercase;
        font-size: 14px;
        font-weight: bold;
    }
}

header {
    padding: 20px 0;
    .row{
        align-items: center;
    }
}

</style>