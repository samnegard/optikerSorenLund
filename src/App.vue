<template>
    <v-app light>
        <v-content>
            <osl-header />
            <osl-page id="prices" :align-center="false" :justify-center="false">
                <osl-page-header title="Vi hjälper dig att se bättre ut">
                    <div class="headline mt-2 blue-grey--text">
                        Välkommen in!
                    </div>
                </osl-page-header>
                <v-flex xs12 md4>
                    <v-card class="elevation-0 transparent">
                        <v-card-title primary-title class="layout justify-center">
                            <div class="headline">Omtanke</div>
                        </v-card-title>
                        <v-card-text class="px-0 text-xs-center text-sm-left">
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
                        <v-card-text class="px-0 text-xs-center text-sm-left">
                            Då vi inte tummar på kvalitén använder vi endast högkvalitativa glas från Zeiss.
                            Givetvis kan vi erbjuda den senaste teknologin inom progressiva glasögon.
                            Plus kanske något om linser.
                        </v-card-text>
                    </v-card>
                </v-flex>
                <v-flex xs12 md4>
                    <v-card class="elevation-0 transparent">
                        <v-card-title primary-title class="layout justify-center">
                            <div class="headline">Service</div>
                        </v-card-title>
                        <v-card-text class="px-0 text-xs-center text-sm-left">
                           Vi finns i centrum med ett brett utbud av de senaste kollektionerna och välkända varumärken toppat med personlig och professionell service.
                            Från allra första stund. Hos oss hittar du det senaste modet för alla smaker och personligheter. Välkommen.
                        </v-card-text>
                    </v-card>
                </v-flex>
            </osl-page>
            <osl-page id="prices" :align-center="false">
                <osl-page-header title="Lite om våra priser" />
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
            </osl-page>

            <osl-quote src="src/assets/section.jpg">Alltid trevliga och tillmötesgående</osl-quote>

            <osl-page id="glases">
                <osl-page-header title="Glasögon" />
                <v-flex xs12 xl10>
                    <v-layout row wrap justify-space-between aling-center>
                        <v-flex xs12 xl10>
                            <v-layout row wrap justify-space-between align-center>
                                <v-flex xs12 md3 order-xs1 order-md2>
                                    <v-card flat class="transparent">
                                        <v-card-media src="src/assets/glasses.png" height="300px" contain></v-card-media>
                                    </v-card>
                                </v-flex>
                                <v-flex xs12 md8 order-xs2 order-md1>
                                    <v-card flat color="transparent">
                                        <v-card-text class="px-0">
                                            Glasögonen ska sitta skönt, passa din personlighet och vara försedda med glas anpassade för just ditt synfel och din livsstil.
                                        </v-card-text>
                                        <v-card-text class="px-0">
                                            Bågarna och glasen skall tillsammans ge dig det ultimata resultatet och fungera i din vardag och det liv du lever.
                                        </v-card-text>
                                        <v-card-text class="px-0">
                                            Hos oss hittar du ett stort urval av bågar och glas.
                                            Glas med olika egenskaper och förmågor och bågar i olika former, mönster och färger.
                                            Allt för att du ska få så stor valfrihet som möjligt.
                                            Vi handplockar våra bågar själva vilket gör att vi hela tiden kan ha de bästa bågarna ur varje kollektion i vår butik.
                                        </v-card-text>
                                        <v-card-text class="px-0">
                                            Då vi inte tummar på kvalitén använder vi endast högkvalitativa glas från Hoya och Rodenstock.
                                            Givetvis kan vi erbjuda den senaste teknologin inom progressiva glasögon.
                                        </v-card-text>
                                        <v-card-text class="px-0">
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
                    <v-container grid-list-md>
                        <v-layout row wrap align-center justify-center>
                            <osl-product-card href="https://www.efvaattling.se/sv/artiklar/ovrigt/glasogon/index.html" src="src/assets/attling.png" />
                            <osl-product-card href="https://dcompanynordic.com/sv/varumarke/norr" src="src/assets/eoe.jpg" />
                            <osl-product-card href="https://www.eoe-glasses.com/" src="src/assets/norr.jpg" />
                            <osl-product-card href="https://www.ray-ban.com/sweden" src="src/assets/rayban.jpg" />
                        </v-layout>
                    </v-container>
                </v-flex>
            </osl-page>

            <osl-page id="lenses">
                <osl-page-header title="Kontaktlinser" />
                <v-flex xs12 xl10>
                    <v-layout row wrap justify-space-between align-center>
                        <v-flex xs12 md4>
                            <v-card flat class="transparent">
                                <v-card-media src="src/assets/lenses.png" height="300px" contain></v-card-media>
                            </v-card>
                        </v-flex>
                        <v-flex xs12 md7>
                            <v-card flat color="transparent" class="pa-0">
                                <v-card-text class="px-0">
                                    Upplev friheten med kontaktlinser!
                                    För dig som lever ett aktivt liv är det ett självklart val och fördelarna är många.
                                    Kontaktlinser är aldrig i vägen, de ger ett obegränsat synfält och de återger omgivningen i naturlig storlek utan förvrängningar.
                                </v-card-text>
                                <v-card-text class="px-0">
                                    Utvecklingen av material och passform gör att dagens linser är lätta att vänja sig vid.
                                    De känns inte och de korrigerar ofta synen bättre än glasögon.
                                    I dag kan nästan alla synfelkorrigeras med kontaktlinser: närsynthet, översynthet, astigmatism och åldersynthet.
                                </v-card-text>
                                <v-card-text class="px-0">
                                    Vi har ett komplett utbud av de senaste kontaktlinserna på marknaden: mjuka linser, endagarslinser, dygnetruntlinser, nattlinser (orto-K), topografitillpassade stabila linser och färgade linser.
                                    Är du åldersynt och är i behov av multifokala linser finns det flera olika alternativ och korrigeringar att tillgå.
                                    Är du osäker på vilken typ som passar dig bäst, eller om du använder rätt linser, är du självklart välkommen in för att få en professionell bedömning!
                                </v-card-text>
                            </v-card>
                        </v-flex>
                    </v-layout>
                </v-flex>
                <v-flex xs12 xl10>
                    <v-container grid-list-md>
                        <v-layout row wrap align-center justify-center>
                            <osl-product-card href="https://www.efvaattling.se/sv/artiklar/ovrigt/glasogon/index.html" src="src/assets/alcon.png" />
                            <osl-product-card href="https://dcompanynordic.com/sv/varumarke/norr" src="src/assets/bauschlomb.png" />
                            <osl-product-card href="https://www.eoe-glasses.com/" src="src/assets/coopervision.png" />
                            <osl-product-card href="https://www.eoe-glasses.com/" src="src/assets/jnj.jpg" />
                        </v-layout>
                    </v-container>
                </v-flex>
            </osl-page>

            <osl-quote src="src/assets/section.jpg">Men hjälp av fantastisk personal fick jag mina glasögon i min smak</osl-quote>

            <osl-page id="who">
                <osl-page-header title="Detta är vi" />
                <v-flex xs12 lg10>
                    <v-layout row wrap justify-center>
                        <v-flex xs12 md5>
                            <v-card>
                                <v-card-media src="src/assets/store.jpg" height="400px"></v-card-media>
                            </v-card>
                        </v-flex>
                        <v-flex xs12 md7>
                            <v-card flat color="transparent">
                                <v-card-text class="pa-0">
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
                            <v-card flat color="transparent">
                                <v-card-text class="px-0 pt-0">
                                    Vi finns på Arklimästaregatan 39 i Karlskrona, där ”bakom Wachtmeister”. Parkera i P-huset i Wachtmeister och ta med biljetten in så ersätter vi för en timmes parkering.
                                </v-card-text>
                                <v-card-text class="px-0 pb-0">
                                    Välkommen in till oss, så tar vi tillsammans reda på hur du egentligen ser ut.
                                </v-card-text>
                            </v-card>
                        </v-flex>
                        <v-flex d-flex xs12 sm5 md4 lg3 xl2>
                            <v-card d-flex>
                                <v-card-media src="src/assets/soren.jpg" height="200px">
                                    <v-container fill-height fluid class="pt-0">
                                        <v-layout fill-height>
                                            <v-flex xs12 align-end flexbox class="pt-2">
                                                <span class="headline white--text">Sören</span>
                                            </v-flex>
                                        </v-layout>
                                    </v-container>
                                </v-card-media>
                                <v-card-actions>
                                    <v-spacer></v-spacer>
                                    <v-btn icon href="mailto:soren@optikersorenlund.se">
                                        <v-icon>mail_outline</v-icon>
                                    </v-btn>
                                </v-card-actions>
                            </v-card>
                        </v-flex>
                        <v-flex d-flex xs12 sm5 md4 lg3 xl2>
                            <v-card d-flex>
                                <v-card-media src="src/assets/lena.jpg" height="200px">
                                    <v-container fill-height fluid class="pt-0">
                                        <v-layout fill-height>
                                            <v-flex xs12 align-end flexbox class="pt-2">
                                                <span class="headline white--text">Lena</span>
                                            </v-flex>
                                        </v-layout>
                                    </v-container>
                                </v-card-media>
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
            </osl-page>

            <div id="map"></div>

            <osl-footer></osl-footer>
        </v-content>
    </v-app>
</template>

<script>
    import OslFooter from './components/osl-footer.vue'
    import OslHeader from './components/osl-header.vue'
    import OslPage from './components/osl-page.vue'
    import OslPageHeader from './components/osl-page-header.vue'
    import OslProductCard from './components/osl-product-card.vue'
    import OslQuote from './components/osl-quote.vue'

    export default {
        components: {
            OslFooter,
            OslHeader,
            OslPage,
            OslPageHeader,
            OslProductCard,
            OslQuote
        },
        data () {
            return {
                dialog: false
            }
        }
    }
</script>
