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
Maakuntakaavan aluevaraus liittyy assosiaatiolla ```maarays``` yhteen tai useampaan sellaiseen [Kaavamaarays](dokumentaatio/#kaavamaarays)-luokan objektiin, jonka ```laji```-attribuutin arvo on jokin [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoista, joka sisältyy määrityshierarkioihin ```Maakuntakaava```. Linjojen ja väylien pääkäyttötarkoitus osoitetaan lisätiedonlajilla [Pääkäyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/paakayttotarkoitus).
{% include common/clause_end.html %}
