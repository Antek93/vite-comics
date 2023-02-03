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
                <div>
                   <a href="#"> digital comics</a>
                </div>
            </div>
            <div>
                <img src="../assets/buy-comics-merchandise.png" alt="">
                <div>
                <a href="#">dc merchandise</a>    
                 </div>
            </div>
            <div>
                <img src="../assets/buy-comics-subscriptions.png" alt="">
                <div>
                    <a href="#">subscription</a> 
                </div>
            </div>
            <div>
                <img id="specificImg" src="../assets/buy-comics-shop-locator.png" alt="">
                <div>
                    <a href="#">comic shop locator</a>
                </div>
            </div>
            <div>
                <img src="../assets/buy-dc-power-visa.svg" alt="">
                <div>
                    <a href="#">dc power visa</a>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../styles/partials/AppMerchandiseAttributes.scss"
</style>
