<template>
    <v-app light>
        <v-content>
            <section>
                <v-parallax src="src/assets/background.jpg" height="700">
                    <v-layout column align-center justify-center class="white--text">
                        <img src="src/assets/logo-full.svg" alt="Optiker Sören Lund" class="mb-2 logo">
                    </v-layout>
                </v-parallax>
            </section>

            <section class="grey lighten-5 pb-5">
                <v-container grid-list-xl>
                    <v-layout row wrap>
                        <v-flex xs12 class="my-4">
                            <div class="text-xs-center blue-grey--text">
                                <h2 class="display-1">Vi hjälper dig att se bättre ut</h2>
                                <div class="headline mt-2">
                                    Välkommen in!
                                </div>
                            </div>
                            <v-divider class="mt-4 blue-grey"></v-divider>
                        </v-flex>
                        <v-flex xs12 md4>
                            <v-card class="elevation-0 transparent">
                                <v-card-title primary-title class="layout justify-center">
                                    <div class="headline text-xs-center">Omtanke</div>
                                </v-card-title>
                                <v-card-text>
                                    Hos oss får du personlig service och omtanke!
                                    I en ombonad och unik miljö gör vi en noggrann synundersökning inkl tryckmätning,
                                    därefter får du hjälp att i lugn och ro välja bland våra handplockade bågar från
                                    t ex EoE, Efva Attling, Norr, Ray-Ban m fl.
                                </v-card-text>
                            </v-card>
                        </v-flex>
                        <v-flex xs12 md4>
                            <v-card class="elevation-0 transparent">
                                <v-card-title primary-title class="layout justify-center">
                                    <div class="headline">Kvalitet</div>
                                </v-card-title>
                                <v-card-text>
                                    Då vi inte tummar på kvalitén använder vi endast högkvalitativa glas från Zeiss.
                                    Givetvis kan vi erbjuda den senaste teknologin inom progressiva glasögon.
                                    Plus kanske något om linser.
                                </v-card-text>
                            </v-card>
                        </v-flex>
                        <v-flex xs12 md4>
                            <v-card class="elevation-0 transparent">
                                <v-card-title primary-title class="layout justify-center">
                                    <div class="headline text-xs-center">Service</div>
                                </v-card-title>
                                <v-card-text>
                                   Vi finns i centrum med ett brett utbud av de senaste kollektionerna och välkända varumärken toppat med personlig och professionell service.
                                    Från allra första stund. Hos oss hittar du det senaste modet för alla smaker och personligheter. Välkommen.
                                </v-card-text>
                            </v-card>
                        </v-flex>
                    </v-layout>
                </v-container>
            </section>

            <section class="light-blue lighten-5 py-5">
                <v-container grid-list-xl class="my-5">
                    <v-layout row wrap justify-center>
                        <v-flex xs12 class="mb-4">
                            <div class="text-xs-center">
                                <h2 class="display-2 cyan--text text--darken-1">Lite om våra priser</h2>
                            </div>
                            <v-divider class="mt-4 cyan darken-1"></v-divider>
                        </v-flex>
                        <v-flex d-flex xs12 md4 xl3>
                            <v-card flat>
                                <v-card-media src="src/assets/glasses.jpeg" height="200px"></v-card-media>
                                <v-card-title primary-title class="pb-0">
                                    <div class="headline mb-0">Glasögon</div>
                                </v-card-title>
                                <v-card-text>
                                    <div>Ett grundpris med tillägg för vissa bågar eller glasögontyper</div>
                                    <div>Enkelslipade: Från 875 kr</div>
                                    <div>Dubbelslipade: 3 500 kr</div>
                                    <div>Progressiva: Från 3 500 kr</div>
                                </v-card-text>
                                <v-card-text>
                                    <div>För ögonundersökning med ögonbottenfotografering och tryckmätning, Båge av svensk design samt</div>
                                    <div>- Gradal Individual Eyefit med antireflexbehandling: 7 500 kr</div>
                                    <div>- Zeiss Digital Lenses med antireflexbehandling: 3 475 kr</div>
                                </v-card-text>
                            </v-card>
                        </v-flex>
                        <v-flex d-flex xs12 md4 xl3>
                            <v-card flat>
                                <v-card-media src="src/assets/lenses.jpeg" height="200px"></v-card-media>
                                <v-card-title primary-title class="pb-0">
                                    <h3 class="headline mb-0">Kontaktlinser</h3>
                                </v-card-title>
                                <v-card-text>
                                    För dig med lite torrare ögon: Fr 163 kr per månad. En traditionell lins du använder när du är vaken.
                                </v-card-text>
                                <v-card-text>
                                    För dig som vill ha det bästa för ögonen: Fr 213 kr per månad. Hög syretransport till hornhinnan. Du kan ha linsen 1 månad. Också när du sover.
                                </v-card-text>
                                <v-card-text>
                                    <div>I priset ingår:</div>
                                    <div>Linser för 6 månader.</div>
                                    <div>Linsvätska (1x355 ml eller 1x60 ml beroende på linstyp).</div>
                                    <div>Synundersökning och kontroller.</div>
                                    <div>Vår goda service.</div>
                                </v-card-text>
                            </v-card>
                        </v-flex>
                        <v-flex d-flex xs12 md4 xl3>
                            <v-card flat>
                                <v-card-media src="src/assets/eyecheck.jpg" height="200px"></v-card-media>
                                <v-card-title primary-title class="pb-0">
                                    <h3 class="headline mb-0">Synundersökning</h3>
                                </v-card-title>
                                <v-card-text>
                                    För körkort: 50 kr
                                </v-card-text>
                                <v-card-text>
                                    För att kolla hur jag ser: 0 kr
                                </v-card-text>
                                <v-card-text>
                                    Med ögonbottenfotografering och tryckmätning: 450 kr
                                </v-card-text>
                                <v-card-text>
                                    Jag vill ha med mig ett recept: 450 kr
                                </v-card-text>
                            </v-card>
                        </v-flex>
                    </v-layout>
                </v-container>
            </section>

            <section>
                <v-parallax src="src/assets/section.jpg" height="380">
                    <v-layout column align-center justify-center>
                        <span style="font-size: 0; line-height: 0; display: block; position: relative;">
                            <v-icon style="position: absolute; font-size: 150px; top: -0.3em; left: 50%; transform: translateX(-50%); line-height: 1;" color="cyan">format_quote</v-icon>
                        </span>
                        <span class="display-1 white--text" style="z-index: 20;">Alltid trevliga och tillmötesgående</span>
                    </v-layout>
                </v-parallax>
            </section>

            <section class="grey lighten-5 py-5">
                <v-container grid-list-xl class="my-5">
                    <v-layout row wrap justify-center>
                        <v-flex xs12 class="mb-4">
                            <div class="text-xs-center">
                                <h2 class="display-2 teal--text text--darken-1">Glasögon</h2>
                            </div>
                            <v-divider class="mt-4 teal darken-1"></v-divider>
                        </v-flex>
                        <v-flex xs12 xl10>
                            <v-layout row wrap justify-space-between aling-center>
                                <v-flex xs12 xl10>
                                    <v-layout row wrap justify-space-between align-center>
                                        <v-flex xs12 md3 order-xs1 order-md2>
                                            <v-card flat class="transparent">
                                                <v-card-media src="src/assets/glasses.png" height="300px"></v-card-media>
                                            </v-card>
                                        </v-flex>
                                        <v-flex xs12 md8 order-xs2 order-md1>
                                            <v-card flat color="transparent">
                                                <v-card-text>
                                                    Glasögonen ska sitta skönt, passa din personlighet och vara försedda med glas anpassade för just ditt synfel och din livsstil.
                                                </v-card-text>
                                                <v-card-text>
                                                    Bågarna och glasen skall tillsammans ge dig det ultimata resultatet och fungera i din vardag och det liv du lever.
                                                </v-card-text>
                                                <v-card-text>
                                                    Hos oss hittar du ett stort urval av bågar och glas.
                                                    Glas med olika egenskaper och förmågor och bågar i olika former, mönster och färger.
                                                    Allt för att du ska få så stor valfrihet som möjligt.
                                                    Vi handplockar våra bågar själva vilket gör att vi hela tiden kan ha de bästa bågarna ur varje kollektion i vår butik.
                                                </v-card-text>
                                                <v-card-text>
                                                    Då vi inte tummar på kvalitén använder vi endast högkvalitativa glas från Hoya och Rodenstock.
                                                    Givetvis kan vi erbjuda den senaste teknologin inom progressiva glasögon.
                                                </v-card-text>
                                                <v-card-text>
                                                    För att du skall hitta din båge hjälper vi dig med utprovning och ärliga smakråd så att du får rätt bågmodell som är klassisk, trendig eller diskret.
                                                    Vi som jobbar i butiken vill att du skall känna dig nöjd med ditt val, känner du dig osäker kan du låna med dig bågar hem.
                                                    Vi slipar och monterar alla glasögon i våra verkstäder, vilket ger dig snabbare leverans av glasögonen.
                                                </v-card-text>
                                            </v-card>
                                        </v-flex>
                                    </v-layout>
                                </v-flex>
                            </v-layout>
                        </v-flex>
                        <v-flex xs12 xl10>
                            <v-container grid-list-xl>
                                <v-layout row wrap align-center justify-center>
                                    <v-flex xs12 md3>
                                        <v-card class="pa-3" href="https://www.efvaattling.se/sv/artiklar/ovrigt/glasogon/index.html">
                                            <v-card-media src="src/assets/attling.png" height="100px" contain></v-card-media>
                                        </v-card>
                                    </v-flex>
                                    <v-flex xs12 md3>
                                        <v-card class="pa-3" href="https://dcompanynordic.com/sv/varumarke/norr">
                                            <v-card-media src="src/assets/norr.jpg" height="100px" contain></v-card-media>
                                        </v-card>
                                    </v-flex>
                                    <v-flex xs12 md3>
                                        <v-card class="pa-3" href="https://www.eoe-glasses.com/">
                                            <v-card-media src="src/assets/eoe.jpg" height="100px" contain></v-card-media>
                                        </v-card>
                                    </v-flex>
                                    <v-flex xs12 md3>
                                        <v-card class="pa-3" href="https://www.ray-ban.com/sweden">
                                            <v-card-media src="src/assets/rayban.jpg" height="100px" contain></v-card-media>
                                        </v-card>
                                    </v-flex>
                                </v-layout>
                            </v-container>
                        </v-flex>
                    </v-layout>
                </v-container>
            </section>

            <section class="light-blue lighten-5 py-5">
                <v-container grid-list-xl class="my-5">
                    <v-layout row wrap justify-center>
                        <v-flex xs12 class="mb-4">
                            <div class="text-xs-center">
                                <h2 class="display-2 cyan--text text--darken-1">Kontaktlinser</h2>
                            </div>
                            <v-divider class="mt-4 cyan darken-1"></v-divider>
                        </v-flex>
                        <v-flex xs12 xl10>
                            <v-layout row wrap justify-space-between align-center>
                                <v-flex xs12 md4>
                                    <v-card flat class="transparent">
                                        <v-card-media src="src/assets/lenses.jpeg" height="300px"></v-card-media>
                                    </v-card>
                                </v-flex>
                                <v-flex xs12 md7>
                                    <v-card flat color="transparent">
                                        <v-card-text>
                                            Upplev friheten med kontaktlinser!
                                            För dig som lever ett aktivt liv är det ett självklart val och fördelarna är många.
                                            Kontaktlinser är aldrig i vägen, de ger ett obegränsat synfält och de återger omgivningen i naturlig storlek utan förvrängningar.
                                        </v-card-text>
                                        <v-card-text>
                                            Utvecklingen av material och passform gör att dagens linser är lätta att vänja sig vid.
                                            De känns inte och de korrigerar ofta synen bättre än glasögon.
                                            I dag kan nästan alla synfelkorrigeras med kontaktlinser: närsynthet, översynthet, astigmatism och åldersynthet.
                                        </v-card-text>
                                        <v-card-text>
                                            Vi har ett komplett utbud av de senaste kontaktlinserna på marknaden: mjuka linser, endagarslinser, dygnetruntlinser, nattlinser (orto-K), topografitillpassade stabila linser och färgade linser.
                                            Är du åldersynt och är i behov av multifokala linser finns det flera olika alternativ och korrigeringar att tillgå.
                                            Är du osäker på vilken typ som passar dig bäst, eller om du använder rätt linser, är du självklart välkommen in för att få en professionell bedömning!
                                        </v-card-text>
                                    </v-card>
                                </v-flex>
                            </v-layout>
                        </v-flex>
                        <v-flex xs12 xl10>
                            <v-card>
                                <v-card-text>
                                    Linsleverantörer: Alcon, Bausch & Lomb, Biolens, Consol, Cooper Vision, Hydrolens och Johnson & Johnson?
                                </v-card-text>
                            </v-card>
                        </v-flex>
                    </v-layout>
                </v-container>
            </section>

            <section>
                <v-parallax src="src/assets/section.jpg" height="380">
                    <v-layout column align-center justify-center>
                        <span style="font-size: 0; line-height: 0; display: block; position: relative;">
                            <v-icon style="position: absolute; font-size: 150px; top: -0.3em; left: 50%; transform: translateX(-50%); line-height: 1;" color="cyan">format_quote</v-icon>
                        </span>
                        <span class="display-1 white--text" style="z-index: 20;">Men hjälp av fantastisk personal fick jag mina glasögon i min smak</span>
                    </v-layout>
                </v-parallax>
            </section>

            <section class="grey lighten-5 py-5">
                <v-container grid-list-xl class="my-5">
                    <v-layout row wrap justify-center>
                        <v-flex xs12 class="mb-4">
                            <div class="text-xs-center">
                                <h2 class="display-2 teal--text text--darken-1">Detta är vi</h2>
                            </div>
                            <v-divider class="mt-4 teal darken-1"></v-divider>
                        </v-flex>
                        <v-flex xs12 lg10>
                            <v-layout row wrap justify-center>
                                <v-flex xs12 md5>
                                    <v-card>
                                        <v-card-media src="src/assets/store.jpg" height="400px"></v-card-media>
                                    </v-card>
                                </v-flex>
                                <v-flex xs12 md7>
                                    <v-card flat color="transparent">
                                        <v-card-text>
                                            Historik: Optiker Sören Lund har funnits sedan XXXX. Innan dess fanns Optiker Carl Lund i Kiruna, fanns sedan 1982. Togs över av Sören 1996.
                                            Vi arbetar med märken som bla bla bla. Allt för att bla bla bla.
                                        </v-card-text>
                                    </v-card>
                                </v-flex>
                            </v-layout>
                        </v-flex>
                        <v-flex xs12 lg10>
                            <v-layout row wrap justify-center>
                                <v-flex xs12 md4 lg6 xl8>
                                    <p class="pt-4">Vi finns på Arklimästaregatan 39 i Karlskrona, där ”bakom Wachtmeister”. Parkera i P-huset i Wachtmeister och ta med biljetten in så ersätter vi för en timmes parkering.</p>
                                    <p>Välkommen in till oss, så tar vi tillsammans reda på hur du egentligen ser ut.</p>
                                </v-flex>
                                <v-flex d-flex xs12 sm5 md4 lg3 xl2>
                                    <v-card d-flex flat>
                                        <v-card-media src="src/assets/soren.jpg" height="200px">
                                            <v-container fill-height fluid class="pt-0">
                                                <v-layout fill-height>
                                                    <v-flex xs12 align-end flexbox class="pt-2">
                                                        <span class="headline white--text">Sören</span>
                                                    </v-flex>
                                                </v-layout>
                                            </v-container>
                                        </v-card-media>
                                        <v-card-text>
                                            Sören är legitimerad optiker sedan 199X och har kontaktlinsbehörighet sedan XXXX
                                        </v-card-text>
                                        <v-card-actions>
                                            <v-spacer></v-spacer>
                                            <v-btn icon href="mailto:soren@optikersorenlund.se">
                                                <v-icon>mail_outline</v-icon>
                                            </v-btn>
                                        </v-card-actions>
                                    </v-card>
                                </v-flex>
                                <v-flex d-flex xs12 sm5 md4 lg3 xl2>
                                    <v-card d-flex flat>
                                        <v-card-media src="src/assets/lena.jpg" height="200px">
                                            <v-container fill-height fluid class="pt-0">
                                                <v-layout fill-height>
                                                    <v-flex xs12 align-end flexbox class="pt-2">
                                                        <span class="headline white--text">Lena</span>
                                                    </v-flex>
                                                </v-layout>
                                            </v-container>
                                        </v-card-media>
                                        <v-card-text>
                                            Lena är full av kunskaper för att hjälpa dig med det du behöver
                                        </v-card-text>
                                        <v-card-actions>
                                            <v-spacer></v-spacer>
                                            <v-btn icon href="mailto:lena@optikersorenlund.se">
                                                <v-icon>mail_outline</v-icon>
                                            </v-btn>
                                        </v-card-actions>
                                    </v-card>
                                </v-flex>
                            </v-layout>
                        </v-flex>
                    </v-layout>
                </v-container>
            </section>

            <div id="map"></div>

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
        </v-content>
    </v-app>
</template>

<script>
    export default {
        data () {
            return {
            }
        },
        mounted () {
            initMap()
        }
    }
</script>

<style lang="stylus">
    #map
        width: 100vw
        height: 400px
        background-color: grey
    .logo
        max-width: 100%
        height: auto
</style>
