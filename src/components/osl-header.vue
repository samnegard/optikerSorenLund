<template>
    <section style="position: relative;">
        <v-parallax src="src/assets/background.jpg" height="600">
            <v-layout column align-center justify-center class="white--text">
                <img src="src/assets/logo-full.svg" alt="Optiker Sören Lund" class="mb-2 logo">
            </v-layout>
        </v-parallax>
        <div class="hidden-md-and-up">
            <v-btn small absolute dark fab bottom right color="red darken-1" @click.native.stop="dialog = !dialog">
                <v-icon>phone</v-icon>
            </v-btn>
            <v-dialog v-model="dialog" width="600px">
                <v-card>
                    <v-list class="transparent">
                        <v-list-tile>
                            <v-list-tile-action>
                                <v-icon>phone</v-icon>
                            </v-list-tile-action>
                            <v-list-tile-content>
                                <v-list-tile-title class="grey--text text--darken-4">0455 - 31 13 34</v-list-tile-title>
                            </v-list-tile-content>
                        </v-list-tile>
                        <v-list-tile>
                            <v-list-tile-action>
                                <v-icon>place</v-icon>
                            </v-list-tile-action>
                            <v-list-tile-content>
                                <v-list-tile-title class="grey--text text--darken-4">Arklimästaregatan 39</v-list-tile-title>
                                <v-list-tile-sub-title class="grey--text text--darken-1">371 36 Karlskrona</v-list-tile-sub-title>
                            </v-list-tile-content>
                        </v-list-tile>
                        <v-list-tile>
                            <v-list-tile-action>
                                <v-icon>email</v-icon>
                            </v-list-tile-action>
                            <v-list-tile-content>
                                <v-list-tile-title><a href="mailto:soren@optikersorenlund.se" title="Skicka mail till oss" class="grey--text text--darken-4">soren@optikersorenlund.se</a></v-list-tile-title>
                            </v-list-tile-content>
                        </v-list-tile>
                    </v-list>
                    <v-card-actions>
                        <v-btn flat color="orange" @click.native="dialog = false">Stäng</v-btn>
                    </v-card-actions>
                </v-card>
            </v-dialog>
        </div>
    </section>
</template>
<script>
    export default {
        data () {
            return {
                dialog: false
            }
        }
    }
</script>
