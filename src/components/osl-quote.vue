<template>
    <section class="quote">
        <v-parallax :src="src" :height="height">
            <v-layout column align-center justify-center>
                <span class="quote__icon-container">
                    <v-icon class="quote__icon-container__icon" color="cyan">format_quote</v-icon>
                </span>
                <span class="display-1 white--text quote__icon-container__text">
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
        },
        props: {
            'src': {
                type: String,
                required: true,
                default: 'src/assets/section.jpg'
            },
            'height': {
                type: Number,
                required: false,
                default: 400
            }
        }
    }
</script>

<style lang="stylus">
    .quote__icon-container
        font-size: 0
        line-height: 0
        display: block
        position: relative
    .quote__icon-container__icon
        position: absolute
        font-size: 150px
        top: -0.3em
        left: 50%
        transform: translateX(-50%)
        line-height: 1
    .quote__icon-container__text
        z-index: 20
</style>