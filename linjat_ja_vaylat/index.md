---
layout: "default"
description: ""
id: "linjat_ja_vaylat"
status: "Ehdotus"
---
# Maakuntakaavan linjat ja väylät
{:.no_toc}

<!-- Kommentti ei ollut Ak/yk-työstössä -->

{% include common/clause_start.html type="req" id="sp-mk/vaat-linjat-vaylat-kohde" %}
Maakuntakaavassa linjat ja väylät on {% include common/moduleLink.html moduleId="kaavatiedot" path="dokumentaatio/#kaavakohde" title="Kaavakohde" %}-luokan objekti, jonka ```geometria```-attribuutin kuvaama geometria on viivamainen.

{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-mk/vaat-aluevaraus-maar" %}
Maakuntakaavan aluevaraus liittyy assosiaatiolla ```maarays``` yhteen tai useampaan sellaiseen [Kaavamaarays](dokumentaatio/#kaavamaarays)-luokan objektiin, jonka ```laji```-attribuutin arvo on jokin [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoista, joka sisältyy määrityshierarkioihin ```Maakuntakaava```. 
{% include common/clause_end.html %}

Linjoihin ja väyliin liittyy usein seuraavat lisätiedonlajit:
- [uusi](linkki?)
- [parannettava](?)
- [ohjeellinen sijainti](?)

Huomiona. Kaksiajoratainen päätie/-katu muodostetaan koodistojen avulla seuraavasti kaavamääräsyryhmäksi:
[Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays) [PaaKatu](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/paaKatu)
[Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays) [AjoratojenMaara](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/ajoratojenMaara), on Suure eli [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/)-koodiston koodi, jotka sisältyvät määrityshierarkiaan ```Suure```. Ja sille voi antaa
```arvo```-attribuutin arvona saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kertoo kaistojen määrän sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#integer" title="Integer" %}-rajapinta. Yksikköä ei käytetä. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}. Eli kysesessä tapauksessa se saa Arvon: 2
