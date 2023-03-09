---
layout: "default"
description: ""
id: "aluevaraukset"
status: "Ehdotus"
---
# Maakuntakaavan aluevaraukset

<!-- Kommentti / Ak/yk-työstä poimittu: - halutaanko eroon erillisistä aluevaraus / alueen käyttötarkoitus jne termeistä eri kaavatasojen välillä? Nyt tässä vanha oletus pohjalla -->

{% include common/clause_start.html type="req" id="sp-mk/vaat-aluemainen-aluevaraus" %}
Maakuntakaavan aluevaraus on {% include common/moduleLink.html moduleId="kaavatiedot" path="dokumentaatio/#kaavakohde" title="Kaavakohde" %}-luokan objekti, jonka ```geometria```-attribuutin kuvaama geometria on aluemainen tai pistemäinen. Tai aluemainen geometria voidaan visualisoinnissa generoida pisteeksiAluevaraukset ovat maakuntakaavassa usein olemassa olevia jo muilla kaavatasoilla määriteltyjä varauksia

{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-mk/vaat-aluevaraus-maar" %}
Maakuntakaavan aluevaraus liittyy assosiaatiolla ```maarays``` yhteen tai useampaan sellaiseen [Kaavamaarays](dokumentaatio/#kaavamaarays)-luokan objektiin, jonka ```laji```-attribuutin arvo on jokin [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoista, joka sisältyy määrityshierarkioihin  ```Aluevaraus``` ja ```Maakuntakaava```. Aluevarauksen pääkäyttötarkoitus osoitetaan lisätiedonlajilla [Pääkäyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/paakayttotarkoitus).
{% include common/clause_end.html %}

Huomiona Kaavamääräyslajin arvoista: Maakuntakaavoituksessa aluevarausten osalta käytetään usein ylimmän hierarkiatason kaavamääräyslajeja (esim. AsumisenAlueita voidaan esittää, mutta maakuntakaavatasolla ei esitetä esimerkiksi AsuinPienTaloAlueita)

Aluevaraukset ovat maakuntakaavassa usein olemassa olevia jo muilla kaavatasoilla määriteltyjä varauksia. Niihin ei tule yleensä mitään suureita, poikkeuksen muodostaa
[Tuulivoimaloiden määrä -suure](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/tuulivoimaloidenMaara). 
