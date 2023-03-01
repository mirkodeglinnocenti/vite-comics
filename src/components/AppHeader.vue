<template>
    
    <header>
        <div class="container">
            <div class="row justify-content-between">

                <div>
                    <img class="logo-img" src="/img/dc-logo.png" alt="logo DC Comics">
                </div>

                <ul class="menu-list">
                    <li><a href="#">menu 1</a></li>
                    <li><a href="#">menu 2</a></li>
                    <li><a href="#">menu 3</a></li>
                    <li><a href="#">menu 4</a></li>
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
@use '../style/general.scss' as*;


.logo-img{
    max-width: 80px;
    display: block;
}

.menu-list{
    display: flex;
    flex-wrap: wrap;

    li{
        margin: 0 17px;
    }
}

header {
    padding: 20px 0;
    .row{
        align-items: center;
    }
}

</style>