<template>

    <main>
        <section>
            <div class="container">
                <p class="text-example"> --> Content goes Here &lt;-- </p>
            </div>
        </section>
    </main>

</template>


<script>
export default {

}
</script>

<style lang="scss" scoped>
@use '../style/general.scss' as *;
@use '../style/partials/reset' as *;

section {
    height: 132px;
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

</style>