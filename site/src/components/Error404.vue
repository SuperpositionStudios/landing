<template>
    <div class="layout-view">
        <div class="layout-padding">
            <h1 class="text-white text-center">Oh no!</h1>
            <p class="text-white text-center">You fell into the blackhole, yo</p>
            <button class="clear text-white full-width" @click="goBack">Go Back</button>
        </div>
    </div>
</template>

<script>
    export default {
        data () {
            return {}
        },
        methods: {
            goBack () {
                window.history.go(-1)
            }
        }
    }
</script>

<style lang="stylus">
    body {
        background-image: url('../assets/404.jpg');
        background-repeat: no-repeat;
        background-position: center;
    }

    h1 {
        margin-top: 10%;
    }

    button {
        margin-top: 20%
        border-style: solid;
        border-color: #FFFFFF;
        border-width: 2px;
    }
</style>
