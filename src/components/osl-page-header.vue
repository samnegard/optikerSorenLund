<template>
    <v-flex xs12 class="mb-4">
        <div class="text-xs-center">
            <h2 class="display-2 teal--text text--darken-1">
                <slot></slot>
            </h2>
        </div>
        <v-divider class="mt-4 teal darken-1"></v-divider>
    </v-flex>
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