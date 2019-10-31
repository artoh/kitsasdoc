# Tilikartta

## Tilikartan muokkaaminen

![](tilikartta1.png)

Tilikarttaan voi lisätä uusia tilejä sekä muokata ja poistaa vanhoja.

!!! success "Valmiit tilikartat"
    Lähes kaikki tarvitsemasi tilit löytyvät valmiista tilikartoista, joissa tilien määritykset ovat valmiiksi kohdallaan. Jos lisäät itse tilejä, ole huolellinen numeroinnin ja määritysten kanssa, jotta kirjaukset tulevat käsitellyiksi oikein!

Jos tilikartassa oleva tili on tarpeeton **piilota** se. Piilotettu tili ei näy luetteloissa tiliä valittaessa. Tilin voi myös kokonaan poistaa, mutta yleensä piilottaminen on parempi vaihtoehto.

Voit merkitä paljon käytetyt tilit **suosikkitileiksi**. Tiliä valittaessa voit näyttää pelkät suosikkitilit.

Ylärivin kuvakkeilla määritellään, näytetäänkö **kaikki tilit**, **käytettävissä olevat tilit** (tilit, joita ei ole piilotettu) tai ainoastaan **suosikkitilit**.

Sininen info-kuvake luettelossa merkitsee, että tilille on annettu kirjausohje.

![](otsikko.png)

Tilit ja otsikot pitää **numeroida**. Taseen vastaavaa-tilit alkavat numerolla 1 ja vastattavaa-tilit numerolla 2. Numerosarjat 3..9 kuuluvat tuloslaskelmaan päätettäville tulo- ja menotileille.

Kitupiikissä tilinumeron pituus on enintään kahdeksan numeroa. Tilinumeron lopussa olevat nollat eivät ole merkityksellisiä, eli tilit 4910 ja 49100 tarkoittavat samaa tiliä. Otsikolla saa olla sama numero, kuin sen alle tulevalla tilillä.

Tilejä lisättäessä on tärkeää, että tili tulee oikealle numeroalueelle, jotta se näkyy raporteissa oikealla tavalla. Tilinmuokkauksen **kuuluu otsikolle**-kenttä kertoo, minkä otsikon alle tili kuuluu. Otsikon alle kuuluvat tilit, joiden numerot alkavat otsikon numerosta ja päättyvät viimeiseen **otsikkoväli päättyy**-alkuiseen tiliin eli esimerkissä Konserniavustuksiin kuuluvat kaikki 958-alkuiset tilit.

**Täydentävä teksti** tulostuu tase-erittelylle ja **kirjausohje** on luettavissa tiliä valittaessa.

!!! note "Tilien sijoittuminen tilinpäätöksessä ja taseessa"
    Jos tilien numerointia muutetaan tai tilejä lisätään olemassa olevien otsikkoalueiden ulkopuolelle, pitää vastaavat muutokset tehdä myös [raporttien muokkauksessa](../raportit).

![](myynti.png)

**Tilityyppi** määrittelee, miten tiliä käsitellään kirjanpidossa ja missä luetteloissa tili näytetään, katso alempaa [Tilityypit](#tilityypit).

**Vastatili** määrittää sen, mikä tili valitaan oletuksena tehtäessä tälle tilille kirjaus. Meno- ja tulotileille kannattaa usein valita vastatiliksi pankki- tai käteistili taikka suoritusperusteisessa kirjanpidossa myyntisaatavien tai ostovelkojen tili.

**Verolaji** ja **veroprosentti** ovat tilin kirjauksen oletusvalintoja, verolajin ja -prosentin voi aina valita joka viennille erikseen, katso [arvonlisävero](/alv). Valinnat eivät ole näkyvissä, jos yritystä ei ole merkitty [perusvalinnoissa](../perusvalinnat) arvonlisävelvolliseksi.

Pankkitileille syötetään lisäksi **IBAN-tilinumero**. Tilinumero tarvitaan maksujen kohdentamiseen maksuja
ja tiliotteita tuotaessa.

## Tase-erittely ja tase-erät

![](myyntisaamiset.png)

Tasetilien (vastaavaa ja vastattavaa) kohdalla valitaan, miten tili esitetään **tase-erittelyssä**.

* **Täysi erittely tase-erillä**: Tilin kirjaukset jaetaan eri tase-eriin, joiden kaikkia muutoksia seurataan. Käytetään esimerkiksi tasaeräpoistettavan omaisuuden kirjanpitoarvon seurantaan.
* **Tase-erien luettelo**: Kirjaukset jaetaan tase-eriksi, ja erittelyssä seurataan eri erien saldoja. Käytetään esimerkiksi myyntisaamisissa ja ostoveloissa, jolloin erittelyistä selviää, mitkä saatavat ovat vielä maksamatta.
* **Lisäykset ja vähennykset**: Kirjauksia ei eritellä, mutta tase-erittelyyn tulostuvat tilikauden aikaiset tapahtumat. Käytetään esimerkiksi menojäännöspoistettavissa tileissä.
* **Saldo**: Tase-erittelyyn tulostetaan vain tilien saldot.

Tasetileille on erikseen merkittävä, jos [kohdennukset](../kohdennukset) on käytettävissä.

## Poistettava omaisuus

![](kalusto.png)

Kitupiikki tukee suunnitelman mukaisten poistojen tekemistä tasaeräpoistoina tai menojäännöspoistoina.

**Tasaeräpoistoissa** jokaista tase-erää (hankintaa) seurataan erikseen, ja hankintahinta jaetaan poistoajalle (euromäärä kuukautta kohti). Tilin asetuksissa määritellän poistoajan oletus, mutta poistoaika on määriteltävissä erikseen jokaiselle erälle (hankinnalle).

**Menojäännöspoistossa** aina tilikauden lopussa poistetaan määritelty prosenttiosuus tilin senhetkisestä saldosta. Prosentti on tilikohtainen ja määritellään kohdassa **menojäännöspoisto**.

**Poistotili** määrittää, mille menotilille vuotuiset poistot kirjataan.


## Tilityypit

Koodi | Tilityyppi | Ryhmä | Huomautukset
------|------------|-------|----------
A     | Vastaavaa  | Vastaavaa | Vastaavaa-tili ilman tarkempaa erittelyä
APM   | Poistokelpoinen omaisuus, menojäännöspoisto | Vastaavaa |
APT   | Poistokelpoinen omaisuus, tasapoisto | Vastaavaa |
AS    | Saatavaa  | Vastaavaa | Saatavat ilman tarkempaa erittelyä
AO    | Myyntisaatava | Vastaavaa | Laskutettu myynti
AL    | Arvonlisäverosaatava | Vastaavaa | Vain yksi tili. Tälle tilille kirjataan palautettavan arvonlisäveron osuus ennen alv-ilmoituksen antamista. Tilille saa tehdä vain sellaisia kirjauksia, joihin on määritelty oikeat alv-tunnistetiedot.
ALM   | Maksuperusteisen alv:n kohdentamaton saatava | Vastaavaa | Vain yksi tili. Tälle tilille kirjataan maksuperusteista arvonlisäveromenettelyä käytettäessä kohdentamaton arvonlisäverosaaminen. Kun maksu on suoritettu, siirretään erä arvonlisäverosaatavien tilille. Tilille saa tehdä vain kirjauksia oikeanlaisilla alv-ohjaustiedoilla.
ARK   | Käteisvarat | Vastaavaa |
ARP   | Pankkitili | Vastaavaa  |
AV    | Verosaatava | Vastaavaa | Vain yksi tili. Saatava verottajalta, jos palautettavia veroja on maksettavia enemmän.
B     | Vastattavaa | Vastattavaa | Vastattavaa-tili ilman tarkempaa erittelyä
BE    | Edellisten tilikausien voitto/tappio | Vastattavaa | Vain yksi tili. Edellisten tilikausien yli/alijäämä tulee näkyviin tälle tilille.
T     | Tämän tilikauden tulos | Vastattavaa | Vain yksi tili. Tämän tilikauden tulos tulee näkyviin tälle tilille. Tilille ei saa tehdä mitään kirjauksia.
BS    | Velat | Vastattavaa | Velat ilman tarkempaa erittelyä
BL    | Arvonlisäverovelka | Vastattavaa | Vain yksi tili. Tälle tilille kirjataan arvonlisäveron osuus ennen alv-ilmoituksen antamista. Tilille saa tehdä vain sellaisia kirjauksia, joihin on merkitty oikeat alv-ohjaustiedot.
BLM  | Maksuperusteisen alv:n kohdentamaton velka | Vastattavaa  | Vain yksi tili. Tälle tilille kirjataan maksuperusteista arvonlisäveromenettelyä käytettäessä kohdetamaton arvonlisäverovelka. Kun myynnistä on saatu maksu, siirretään erä arvonlisäverovelan tilille.
BO   | Ostovelka | Vastattavaa | Maksamattomat ostolaskut
BV   | Verovelka | Vastattavaa | Vain yksi tili. Oma-aloitteisesti maksettavat verot (esim. arvonlisävero ja ennakonpidätykset), jotka on ilmoitettu mutta ei vielä maksettu. Vastaa OmaVero-tilin velkasaldoa.
C    | Tulot    | Tulo   | Tulot, joita ei lasketa liikevaihtoon
CL   | Liikevaihtotulo | Tulo | Liikevaihtoon laskettava myynti
D    | Menot  | Meno |
DP   | Poistot | Meno  | Poistojen menotili


## Tilikartan vieminen

![](vienti.png)

**Vie tilikartta**-painikkeellä pääset viemään tilikartan tilit, tositelajit, raportit, tilinpäätöspohjan ja joukon muita valintoja ktk-tiedostoksi, jonka pohjalta voi aloittaa uuden kirjanpidon.

Näin voit siirtää kirjanpitosi valinnat toiseen kirjanpitoon tai jakaa tilikarttasi muiden Kitupiikin käyttäjien kanssa.

Painike käynnistää sarjan valintaikkunoita, joissa valitset tilikartalle nimen ja kirjoitat tilikartan ohjeet.

## Tilikartan päivittäminen

Kun ohjelman päivityksen myötä myös käytössäsi oleva tilikartta on päivittynyt, saat siitä aloitusnäyttöön ilmoituksen

![](paivitettavissa.png)

Tilikarttamääritysten **Päivitä tilikartta**-valinnasta pääset päivittämään tilikartan uudempaan.

Päivitystoiminto
* Lisää tilikarttaan uudet tilit
* Päivittää niiden tilien tiedot (nimi, kirjausohje yms.), joita käyttäjä ei ole itse muokannut. Käyttäjän muokkaamien tilien tietoja ei päivitetä
* Päivittää raportit ja tilinpäätöksen pohjan

![](paivitys.png)

**Päivitä ohjelman sisäiseen tilikarttaan** päivittää ohjelman mukana tulleeseen tilikarttaan. **Päivitys tiedostossa olevaan tilikarttaan** mahdollistaa tilikartan lataamisen ktk-tiedostosta.

!!! warning "Varmista tiedoston sopivuus"
    Ohjelman sisäisissä päivityksissä on varmistettu, että päivitys sopii käytössä olevaan tilikarttaan. Jos päivität erilliseen tiedostoon, varmista tiedoston sopivuus (ettet esimerkiksi päivitä osakeyhtiölle yhdistyksen tilikarttaa).

![](korvaukset.png)

Jos olet muokannut itse raportteja tai tilinpäätöksen pohjaa, joudut valitsemaan, korvataanko muokatut raportit/pohjat päivitetyillä vai säästetäänkö muokkaamasi versiot.

!!! tip "Muokattujen raporttien säilyttäminen"
    Voit säilyttää muokatut raporttisi nimeämällä ne uudelleen ennen päivitystä
