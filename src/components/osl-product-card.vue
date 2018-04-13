<template>
    <v-flex xs12 sm6 md3>
        <v-card class="pa-3" :href="href" target="_blank">
            <v-card-media :src="src" height="100px" contain></v-card-media>
        </v-card>
    </v-flex>
</template>
<script>
    export default {
       props: {
            'href': {
                type: String,
                required: true
            },
            'src': {
                type: String,
                required: true
            }
        }
    }
</script>
