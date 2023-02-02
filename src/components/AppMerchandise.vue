<script>
export default {
    name: 'AppMerchandise',
    data () {
        return {
            msg: 'Ciao',
            count: 0,
        }

    }
};
</script>


<template>
    <div class="container">
        <div class="boxPictures">
            <div>
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <div>digital comics</div>
            </div>
            <div>
                <img src="../assets/buy-comics-merchandise.png" alt="">
                <div>dc merchandise</div>
            </div>
            <div>
                <img src="../assets/buy-comics-subscriptions.png" alt="">
                <div>subscription</div>

            </div>
            <div>
                <img id="specificImg" src="../assets/buy-comics-shop-locator.png" alt="">
                <div>comic shop locator</div>
            </div>
            <div>
                <img src="../assets/buy-dc-power-visa.svg" alt="">
                <div>dc power visa</div>

            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../styles/partials/AppMerchandiseAttributes.scss"
</style>
