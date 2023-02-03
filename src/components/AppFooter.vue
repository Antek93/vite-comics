<script>
export default {
    name: 'AppFooter',
    data () {
        return {
            msg: 'Ciao',
            count: 0,
        }

    }
};
</script>


<template>
    <div class="containerPrincipale">
        <div class="containerIntermedio">
            <div class="linksLogo">
                <div class="links">
                    <div>
                        <div class="title">dc comics</div>
                        <ul>
                            <li>
                                <a href="#">Characters</a>
                            </li>
                            <li>
                                <a href="#">Comics</a>
                            </li>
                            <li>
                                <a href="#">Movies</a>
                            </li>
                            <li>
                                <a href="#">TV</a>
                            </li>
                            <li>
                                <a href="#">Games</a>
                            </li>
                            <li>
                                <a href="#">Videos</a>
                            </li>
                            <li>
                                <a href="#">News</a>
                            </li>
                        </ul>
                        <div class="title space">shop</div>
                        <ul>
                            <li>
                                <a href="#">Shop DC</a>
                            </li>
                            <li>
                                <a href="#">Shop DC Collectibles</a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <div class="title">dc</div>
                        <ul>
                            <li>
                                <a href="#">Terms of Use</a>
                            </li>
                            <li>
                                <a href="#">Privacy policy (New)</a>
                            </li>
                            <li>
                                <a href="#">Ad Choices</a>
                            </li>
                            <li>
                                <a href="#">Advertising</a>
                            </li>
                            <li>
                                <a href="#">Jobs</a>
                            </li>
                            <li>
                                <a href="#">Subscriptions</a>
                            </li>
                            <li>
                                <a href="#">Talent Workshops</a>
                            </li>
                            <li>
                                <a href="#">CPSC Certificates</a>
                            </li>
                            <li>
                                <a href="#">Ratings</a>
                            </li>
                            <li>
                                <a href="#">Shop Help</a>
                            </li>
                            <li>
                                <a href="#">Contact Us</a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <div class="title">sites</div>
                        <ul>
                            <li>
                                <a href="#">DC</a>
                            </li>
                            <li>
                                <a href="#">MAD Magazine</a>
                            </li>
                            <li>
                                <a href="#">DC Kids</a>
                            </li>
                            <li>
                                <a href="#">DC Universe</a>
                            </li>
                            <li>
                                <a href="#">DC Power Visa</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="logo">
                    <img src="../assets/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
        <div class="signUp">
            <div class="boxadvs">
                <div class="now-btn">
                    <button>
                        SIGN-UP NOW!
                    </button>
                </div>
                <div class="follow-btn">
                    <div>
                        FOLLOW US
                    </div>
                    <div>
                        <img src="../assets/footer-facebook.png" alt="">
                    </div>
                    <div>
                        <img src="../assets/footer-twitter.png" alt="">
                    </div>
                    <div>
                        <img src="../assets/footer-youtube.png" alt="">
                    </div>
                    <div>
                        <img src="../assets/footer-pinterest.png" alt="">
                    </div>
                    <div>
                        <img src="../assets/footer-periscope.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../styles/partials/AppFooterAttributes.scss"
</style>
