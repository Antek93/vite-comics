<script>
export default {
    name: 'AppMain',
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
            --> Content goes here
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container {
    background-color: black;
    width: 100%;
    height: 15vh;
    color: white;
    display: flex;
    align-items: center;
    div {
        width: 70%;
        margin: 0 auto;
        font-size: 20px;
        
    }
}
</style>
