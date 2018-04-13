<template>
    <section class="grey lighten-5 py-5" :id="id">
        <v-container grid-list-xl class="my-5">
            <v-layout row wrap justify-center>
                <slot></slot>
            </v-layout>
        </v-container>
    </section>
</template>
<script>
    export default {
        props: ['color', 'id'],
        data () {
            return {
            }
        }
    }
</script>

<style></style>