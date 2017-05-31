<template>
    <q-layout>
        <div slot="header" class="toolbar">
            <q-toolbar-title :padding="0">
                Superposition Studios - Landing
            </q-toolbar-title>
        </div>

        <div class="layout-view">
            <q-parallax src="../statics/landing.jpg">
                <div slot="loading">Loading...</div>
                <h1 class="text-white border-black">Hello.</h1>
            </q-parallax>

            <div class="layout-padding">
                <h1 class="text-center">Our Team</h1>
                <p class="text-center">John</p>
                <p class="text-center">Caleb</p>
                <p class="text-center">Finn</p>
                <p class="text-center">Matt</p>
            </div>
        </div>
    </q-layout>
</template>

<script>
    export default {
        data () {
            return {}
        }
    }
</script>

<style>
    i {
        font-size: 3em;
        margin-left: 43%;
    }

    .border-black {
        text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
    }
</style>
