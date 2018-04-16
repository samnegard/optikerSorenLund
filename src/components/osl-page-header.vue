<template>
    <v-flex xs12 class="mb-4">
        <div class="text-xs-center">
            <h2 :class="headerColorClass" class="display-1">
                {{ title }}
            </h2>
            <slot></slot>
        </div>
        <v-divider :class="color" class="mt-4"></v-divider>
    </v-flex>
</template>
<script>
    export default {
        props: {
            'color': {
                type: String,
                required: false,
                default: 'blue-grey'
            },
            'title': {
                type: String,
                required: true
            }
        },
        computed: {
            headerColorClass () {
                return this.color + '--text'
            }
        }
    }
</script>
