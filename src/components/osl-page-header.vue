<template>
    <v-flex xs12 class="mb-4">
        <div class="text-xs-center">
            <h2 :class="headerColorClass" class="display-2 text--darken-1">
                <slot></slot>
            </h2>
        </div>
        <v-divider :class="color" class="mt-4 darken-1"></v-divider>
    </v-flex>
</template>
<script>
    export default {
        props: {
            'color': {
                type: String,
                required: false,
                default: 'teal'
            }
        },
        computed: {
            headerColorClass () {
                return this.color + '--text'
            }
        }
    }
</script>
