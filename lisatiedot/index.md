---
layout: "default"
description: ""
id: "lisatiedot"
status: "Ehdotus"
---

# Kaavamääräyksen lisätiedot
{:.no_toc}

## Tyyppi
Kaavamääräyksen tarkempi tyypittely. Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

### Pääkäyttötarkoitus
Kaavamääräyksen lisätiedolla [Pääkäyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/paakayttotarkoitus) annotoidaan [Aluevarauksille](../aluevaraukset/index.md) annettuista {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavamaarays" title="Kaavamääräyksistä" %} pääkäyttötarkoitus. Pääkäyttötarkoituksella tarkoitetaan sitä käyttötarkoitusta, johon suhteellisesti suurin osa alueen käytöstä on tarkoitettu. 

{% include common/clause_start.html type="req" id="sp-yk/paakayttotarkoitus" %}
[Aluevarausten](../aluevaraukset/index.md) {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavamaarays" title="Kaavamääräyksistä" %} yhdelle tai useammalle on merkittävä {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatiedoksi" %} [Pääkäyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/paakayttotarkoitus), riippuen siitä, onko {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohteelle" %} osoitettu osuudeltaan yhtäsuureksi tarkoitettuja käyttötarkoituksia.
{% include common/clause_end.html %}

### Osa-alue
Kaavamääräyksen lisätiedolla [Osa-alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/osaAlue) voidaan merkitä luonteeltaan erityisominaisuuksia kuvaavat kaavamääräykset. Maakuntakaavan osa-alueiden erityisominaisuudet voivat liittyä luonnon- tai kulttuuriympäristön, maiseman sekä luonnonvarojen erityisiin arvoihin. Erityisominaisuuksia voivat olla myös osa-alueiden alueidenkäyttöä erityisesti rajoittavat ominaisuudet, kuten melu- ja vaaraalueet tai suojavyöhykkeet. Tähän merkintäryhmään kuuluvat myös rakentamisrajoitusalueen laajentamista tai poistamista koskevat merkinnät

### Ohjeellinen
Kaavamääräyksen lisätiedolla [Ohjeellinen](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/ohjeellinen) voidaan merkitä kohde, joka liittyy kehittämiseen. Se voi olla esimerkiksi ohjeellinen tielinjaus. 

## Tarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/tarve>

Maakuntakaavoissa käytetään paljon jotakin tunnistettua tarvetta kuvaavia kaavamääräyksiä. Tällaiset muodostetaan [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodien ja [Tarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/tarve)-luokan lisätietokoodien yhdistelminä.

Esimerkkejä:<br>
* ```Johdon, putken tai linjan yhteystarve``` voidaan muodostaa liittämällä kaavakohteeseen määräys [Johto, putki tai linja](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/JohtoPutkiTaiLinja) sekä lisätieto [Yhteystarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/yhteystarve). 

* ```Viheryhteystarve``` voidaan muodostaa liittämällä kaavakohteeseen määräys [Ekologinen yhteys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/ekologinenYhteys) sekä lisätieto [Yhteystarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/yhteystarve). Samoin esim. ```virkistysyhteystarve``` voidaan kuvata koodien [Ulkoilu- tai virkistysreitti](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/ulkoiluTaiVirkistysReitti) ja [Yhteystarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/yhteystarve) yhdistelmänä.

* Erityyppiset ```tieliikenteen yhteystarpeet``` saadaan kuvattua väylän toiminnallista luokkaa parhaiten kuvaavan määräyskoodin (esim. [Valtatie](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/valtaTie)) ja lisätiedon [Yhteystarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/yhteystarve) yhdistelmänä.

## Ympäristömuutoksen laji
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/ymparistomuutoksenLaji>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

Ympäristömuutoksen laji -ryhmän lisätietokoodein voidaan täsmentää, miten kaavamääräyksen kuvaama maankäyttö eroaa suhteessa kaavan laadinnan ajanhetkellä olemassa olevaan, kaavakohteen alueella sijaitsevaan maankäyttöön.

Esimerkkejä:

* Määräys [Valtatie](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/valtaTie) + lisätieto [Uusi](<http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/uusi>) = ```Uusi valtatie```.

* Määräys [Valtatie](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/valtaTie) + lisätieto [Parannettava](<http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/uusi>) = ```Parannettava valtatie```.

* Määräys [Toimitilat](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/toimiTilat) + lisätieto [ReserviAlue](<http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/uusi>) = ```Toimitilojen reservialue```.


## Merkittävyys

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/merkittavyys>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

Merkittävyys -ryhmän lisätietokoodein voidaan täsmentää, onko kaavamääräyksellä esimerkiksi maakunnallista tai valtakunnallista merkittävyyttä

Esimerkkejä:

* Määräys [Merkittävä rakennettu kulttuuriympäristö](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/merkittavaRakennettuKulttuuriymparisto) + lisätieto [Valtakunnallinen](<http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/uusi>) = ```Valtakunnallisesti merkittävä rakennettu kulttuuriympäristö```.

## Ympäristöltään säilytettävä alue

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/ymparistoarvojenAlue>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

Ympäristöltään säilytettävä alue -ryhmän lisätietokoodein voidaan täsmentää, pitääkö kaavamääräyksellä huomioida ympäristön säilytettävyys.

Esimerkkejä:

* Määräys [Vesialue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/vesiAlue) + lisätieto [ymparistoltaanSailytettavaAlue](<http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/uusi>) = ```Ympäristöltään säilytettävä vesialue```.
* * Määräys [Maisemallisesti arvokas alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/maisemallisestiArvokasAlue) + lisätieto [ymparistoltaanSailytettavaAlue](<http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/uusi>) = ```Maisemallisesti arvokas alue, ympäristö säilytettävä```.

## Maankäyttörajoitukset: rakentamisrajoitus

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/rakentamisrajoitusMaakuntakaava>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

Rakentamisrajoitus voidaan antaa lisätiedonlajina kaavakohteelle
