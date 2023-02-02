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

        </div>
    </div>
</template>

<style lang="scss" scoped>
.containerPrincipale {
    width: 100%;
    height: 51.5vh;
        .containerIntermedio {
            width: 100%;
            height: 81%;
            padding-top: 3%;
            background-image: url('../assets/footer-bg.jpg');
            background-size: contain;
            .linksLogo {
                width: 70%;
                margin: 0 auto;
                height: 100%;
                display: flex;
                justify-content: center;
                color: white;
                .links {
                    width: 35%;
                    display: flex;
                    justify-content: space-between;
                    align-items: flex-start;
                    ul {
                        list-style: none;
                    }

                    li a {
                        text-decoration: none;
                        color: gray;
                        font-family:'Times New Roman', Times;
                        font-size: 12px;
                    }

                    .title {
                        text-transform: uppercase;
                        font-size: 15px;
                    }

                    .space {
                        margin-top: 10px;
                    }
                
                }
                .logo {
                    width: 75%;
                    position: relative;
                    overflow: hidden;
                    
                    img {
                        position: absolute;
                        width: 62%;
                        top: 0%;
                        left: 30%
                        
                        
                    }
                }
            }
            
        }

        .signUp {
            width: 100%;
            height: 11.9%;
            background-color: rgb(42, 42, 42);
            position: absolute;
            z-index: 2;
        }
    }
</style>
