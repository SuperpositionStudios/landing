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
                <div>
                    <h1 class="text-center">Our Team</h1>
                    <div>
                        <p class="text-center"><strong>John</strong></p>
                        <p class="text-center">In iaculis volutpat neque, ac ultrices nisl condimentum sed. Donec at quam eget nisi aliquam tristique. Duis quis efficitur ante, porta pulvinar mi. Etiam porttitor elementum nibh, eu condimentum eros volutpat vitae. Nunc nec turpis dui.</p>
                    </div>
                    <div>
                        <p class="text-center"><strong>Caleb</strong></p>
                        <p class="text-center">In iaculis volutpat neque, ac ultrices nisl condimentum sed. Donec at quam eget nisi aliquam tristique. Duis quis efficitur ante, porta pulvinar mi. Etiam porttitor elementum nibh, eu condimentum eros volutpat vitae. Nunc nec turpis dui.</p>
                    </div>
                    <div>
                        <p class="text-center"><strong>Finn</strong></p>
                        <p class="text-center">In iaculis volutpat neque, ac ultrices nisl condimentum sed. Donec at quam eget nisi aliquam tristique. Duis quis efficitur ante, porta pulvinar mi. Etiam porttitor elementum nibh, eu condimentum eros volutpat vitae. Nunc nec turpis dui.</p>
                    </div>
                    <div>
                        <p class="text-center"><strong>Matt</strong></p>
                        <p class="text-center">In iaculis volutpat neque, ac ultrices nisl condimentum sed. Donec at quam eget nisi aliquam tristique. Duis quis efficitur ante, porta pulvinar mi. Etiam porttitor elementum nibh, eu condimentum eros volutpat vitae. Nunc nec turpis dui.</p>
                    </div>
                </div>
            </div>

            <q-parallax src="../statics/landing.jpg">
                <div slot="loading">Loading...</div>
                <h1 class="text-white border-black">Our Story.</h1>
            </q-parallax>
            <div class="layout-padding">
                <p class="text-center"> We began this years flex friday with a project named And/Ore. And/Ore was a
                    web based java script game, that was orrigenally intentded as a testing bed for Machine Learning Ai's.
                    This venture was
                </p>
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
