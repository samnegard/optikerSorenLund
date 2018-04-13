<template>
    <section :class="color" class="lighten-5 py-5" :id="id" style="min-height: 100vh">
        <v-container grid-list-xl class="my-5">
            <v-layout row wrap justify-center align-center>
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
            }
        },
        data () {
            return {
            }
        }
    }
</script>
