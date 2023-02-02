<script>
export default {
    name: 'AppHead',
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
        <div>
            <img src="../assets/dc-logo.png" alt="">
        </div>
        <div>
            <ul>
                <div class="linkContainer">
                    <li>
                        <a href="#">characters</a>
                    </li>
                </div>
                <div>
                    <li>
                        <a href="#">comics</a>
                    </li>
                </div>
                <div>
                    <li>
                        <a href="#">movies</a>
                    </li>
                </div>
                <div>
                    <li>
                        <a href="#">tv</a>
                    </li>
                </div>
                <div>
                    <li>
                        <a href="#">games</a>
                    </li>
                </div>
                <div>
                    <li>
                        <a href="#">collectibles</a>
                    </li>
                </div>
                <div>
                    <li>
                        <a href="#">videos</a>
                    </li>
                </div>
                <div>
                    <li>
                        <a href="#">fans</a>
                    </li>
                </div>
                <div>
                    <li>
                        <a href="#">news</a>
                    </li>
                </div>
                <div>
                    <li>
                        <a href="#">shop</a>
                    </li>
                </div>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@import "../styles/partials/AppHeadAttributes.scss";
</style>
