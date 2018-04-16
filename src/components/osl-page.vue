<template>
    <section :class="color" class="lighten-5 py-5" :id="id">
        <v-container grid-list-xl class="my-5">
            <v-layout row wrap :justify-center="justifyCenter" :align-center="alignCenter">
                <slot></slot>
            </v-layout>
        </v-container>
    </section>
</template>
<script>
    export default {
        props: {
            'color': {
                type: String,
                required: false,
                default: 'grey'
            },
            'id': {
                type: String,
                required: true
            },
            'justify-center': {
                type: Boolean,
                required: false,
                default: true
            },
            'align-center': {
                type: Boolean,
                required: false,
                default: true
            }
        },
        data () {
            return {
            }
        }
    }
</script>
