<template>
    <v-footer dark>
        <v-container grid-list-lg>
            <v-layout row wrap justify-center class="my-4">
                <v-flex xs12 sm7 lg4 order-xs1>
                    <v-list class="transparent">
                        <v-list-tile>
                            <v-list-tile-action>
                                <v-icon>phone</v-icon>
                            </v-list-tile-action>
                            <v-list-tile-content>
                                <v-list-tile-title>0455 - 31 13 34</v-list-tile-title>
                            </v-list-tile-content>
                        </v-list-tile>
                        <v-list-tile>
                            <v-list-tile-action>
                                <v-icon>place</v-icon>
                            </v-list-tile-action>
                            <v-list-tile-content>
                                <v-list-tile-title>Arklimästaregatan 39</v-list-tile-title>
                                <v-list-tile-sub-title>371 36 Karlskrona</v-list-tile-sub-title>
                            </v-list-tile-content>
                        </v-list-tile>
                        <v-list-tile>
                            <v-list-tile-action>
                                <v-icon>email</v-icon>
                            </v-list-tile-action>
                            <v-list-tile-content>
                                <v-list-tile-title><a href="mailto:soren@optikersorenlund.se" title="Skicka mail till oss" class="white--text">soren@optikersorenlund.se</a></v-list-tile-title>
                            </v-list-tile-content>
                        </v-list-tile>
                    </v-list>
                </v-flex>
                <v-flex xs12 lg4 order-xs3 order-lg2 class="text-xs-left text-sm-center text-lg-left">
                    <p class="caption grey--text text--lighten-1">Sociala medier</p>
                    <v-btn flat icon href="https://www.facebook.com/OptikerSorenLund/" target="_blank">
                        <v-icon>fa-facebook</v-icon>
                    </v-btn>
                    <v-btn flat icon href="https://www.youtube.com/user/IAmSren" target="_blank">
                        <v-icon>fa-youtube</v-icon>
                    </v-btn>
                </v-flex>
                <v-flex xs12 sm5 lg3 offset-lg1 order-xs2 order-lg3>
                    <p class="caption grey--text text--lighten-1">Öppettider</p>
                    <div class="white--text">Måndag - Fredag: 09.00 - 18.00</div>
                    <div class="white--text">Lördag: 10.30 - 14.00</div>
                    <div class="white--text">Lunchstängt: 13.00 - 14.00</div>
                </v-flex>
            </v-layout>
        </v-container>
    </v-footer>
</template>
