<template>
    <section>
        <v-parallax src="src/assets/section.jpg" height="380">
            <v-layout column align-center justify-center>
                        <span style="font-size: 0; line-height: 0; display: block; position: relative;">
                            <v-icon style="position: absolute; font-size: 150px; top: -0.3em; left: 50%; transform: translateX(-50%); line-height: 1;" color="cyan">format_quote</v-icon>
                        </span>
                <span class="display-1 white--text" style="z-index: 20;">
                    <slot></slot>
                </span>
            </v-layout>
        </v-parallax>
    </section>
</template>
<script>
    export default {
        data () {
            return {
            }
        }
    }
</script>

<style></style>