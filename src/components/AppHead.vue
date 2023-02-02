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
.container {
    width: 100%;
    padding-top: 10px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 15px;
    text-transform: uppercase;
    
    div:first-child {
        display: flex;
        justify-content: flex-start;
    }
    div:last-child *div {
        height: 100px;
        padding: 0px 2px 0px 2px;
        display: flex;
        justify-content: flex-start;
        align-items: center;
    }
    div:last-child *div:hover {
        border-bottom: 4px solid rgb(0, 106, 255);
    }
    div:last-child ul {
        display: flex;
        justify-content: flex-end;
        list-style: none;
        li {
            text-decoration: none;
            padding: 10px;

            a {
                text-decoration: none;
                color: rgb(45, 42, 42);
            }
            a:hover {
                color: blue;
            }
        }
    }
}
</style>
