!!! note "Edistynyt toiminto"
    Sinun ei yleensä tarvitse muokata raportteja.

    Raporttien muokkausta tarvitaan, jos olet muuttanut tilien numerointia tai lisännyt tilejä olemassa olevien otsikkoalueiden ulkopuolelle.

!!! warning "Tilikarttojen päivitykset"
    Tilikartan päivitykset tekevät muutoksia myös raportteihin. Jos päivität myöhemmin tilikartan, saatat joutua tekemään muutokset uudelleen.


![](muokkaus.png)

**Määritykset > Raportit** pääset muokkaamaan raportteja.

* Valitse **Muokka raporttia**-valintalistasta muokattava raportti.
* **Nimike** -napilla pääset muokkaammaan raportilla tulostuvaa otsikkonimikettä sekä käyttäjälle näytettävää muodon nimeä.

!!! warning "Tiedä, mitä teet"
    Ole huolellinen muokatessasi tulosteita. Taseen ja tuloslaskelmat muodot on määrätty kirjanpitoa koskevassa lainsäädännössä.

## Raporttirivin muokkaus

![](rivi.png)

**Tiliväli(t)** määrittää, mitkä tilinumerot kuuluvat tälle raporttiriville. Pelkkä numero tarkoittaa kaikkia näin alkavia tilejä (kuvan esimerkissä riviin kuuluvat kaikki 201- ja 202-alkuiset tilit).

Numerovälit merkitään **3..7** (tarkoittaa kaikkia numeroilla 3, 4, 5, 6, 7 alkavia tilejä). Merkintä **410..412** tarkoittaa tilejä, jotka alkavat 410, 411 tai 412.

Numerot tai numerovälit voi erottaa välilyönnillä `4 5 61..66` tai pilkulla `4,5,61..66`.

Numeroon tai numeroväliin voi liittää **+** merkitsemään tuloja tai **-** merkitsemään menoja. `4+ 5-` tulostaa kaikki neljällä alkavat tulot ja viidellä alkavat menot.

**Laskenta**

* **Summa** tulostaa otsikon ja laskutoimituksen summan
* **Otsikko** tulostaa pelkän otsikon
* **Välisumma** tulostaa kaikkien edeltävien rivien summat, jotka **lasketaan välisummaan**
* Ellei **Näytä tyhjä** ole valittuna, jätetään kaikki sellaiset rivit tulostamatta, joiden summaksu tulee 0.

* Jos raporttia tulostettaessa valitaan erittelyn tulostus, eritellään vielä erikseen tileittäin ne rivit, joilla on merkitty **Erittely**.
