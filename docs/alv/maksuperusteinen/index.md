# Maksuperusteinen arvonlisävero

!!! info ""
    [Verohallinnon ohje maksuperusteisesta arvonlisäverosta](https://www.vero.fi/yritykset-ja-yhteisot/tietoa-yritysverotuksesta/arvonlisaverotus/pienyritykset_voivat_tilittaa_arvonlisa/)

Pienyritykset (liikevaihto alle 500 000 euroa vuodessa) voivat tilittää ostojen ja myyntien arvonlisäverot maksuperusteisesti. Kitsaalla tämä on mahdollista myös niin, että kirjanpito pidetään suoriteperusteisena.

![](maksuperusteinen.png)

Kun yritys saa myyntilaskun, kirjataan arvonlisäveron osuus tilille **Maksuperusteinen alv-velka**. Kun arvonlisäverosta saadaan maksu, siirretään veron osuus tilille **Arvonlisäverovelka** ja vasta nyt vero tulee näkyviin alv-tilitykseen.

Vastaavalla tavalla ostolaskun veron osuus kirjataan ensin tilille **Maksuperusteinen alv-saaminen** ja vasta kun lasku on maksettu, se siirtyy tilille **Arvonlisäverosaatavat**.

Jos teet kirjauksen maksuperusteisesti pankki- tai käteistililtä, ei tällaista erityismenettelyä tarvita.

Arvonlisävero on kuitenkin maksettava viimeistään vuoden kuluttua suoritepäivästä.

Kun verolajina on maksuperusteinen arvonlisävero, käsittelee Kitsas sen automaattisesti laskutuksessa, Tulo- ja Meno-tyyppisissä tositteissa sekä maksettaessa laskuja Siirto-tositteella tai Tiliote-tositteen laskujenmaksutoiminnolla. Käsittely perustuu ohjaustietoihin ja alv-koodeihin.

!!! danger "Älä kirjaa käsin maksuperusteisen arvonlisäveron eriä"
    Maksuperusteinen arvonlisävero edellyttää erityiskäsittelyä siinä vaiheessa, kun lasku- tai suoritusperusteisesti kirjattu erä maksetaan.

Maksuperusteinen arvonlisävero otetaan käyttöön Arvonlisäveron määrityksistä **Maksuperusteinen alv**-rivillä olevasta rataspainikkeesta, josta aukeaa valintaikkuna:

![](malvikkuna.png)

**Maksuperusteinen arvonlisäverotus alkaa**-ruutuun kirjataan sen verokauden ensimmäinen päivä, jonka arvonlisävero tilitetään maksuperusteisena.

Jos maksuperusteisesta arvonlisäverotuksesta siirrytään takaisin suoriteperusteiseen, merkitään **Suoriteperusteiseen arvonlisäveroon palataan**-ruutuun sen verokauden ensimmäinen päivä, jolloin arvonlisävero tilitetään normaalilla tavalla. Tässä alv-tilityksessä maksetaan myös kaikki vielä maksamatta oleva maksuperusteinen arvonlisävero.

!!! note "Tutustu huolella verohallinnon ohjeisiin"
    Ennen maksuperusteiseen arvonlisäverotukseen siirtymistä tutustu huolella verohallinnon ohjeisiin. Huomaa, että myös alv-vähennykset tilitetään maksuperusteisesti (myös osamaksua käytettäessä).

Maksuperusteista arvonlisäveroa käytettäessä et voi käyttää Kitsaassa automaattista **marginaaliverotusmenettelyä**, vaan voittomarginaali on kirjattava käsin.

!!! warning "Alarajahuojennuksen laskelman tarkastaminen"
    Maksuperusteisessa arvonlisäverossa myös alarajahuojennukseen oikeuttava liikevaihto lasketaan maksuperusteisesti. Tarkasta alarajahuojennuslaskelma huolellisesti.
