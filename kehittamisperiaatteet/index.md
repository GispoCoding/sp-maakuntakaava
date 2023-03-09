---
layout: "default"
description: ""
id: "kehittamisperiaatteet"
status: "Ehdotus"
---
# Kaavamääräyslajit - kehittämisperiaatteet
{:.no_toc}

Kehittämisperiaatteet, kuten Kehittämistarve, Yhteystarve ja Selvitystarve,  ovat maakuntakaavoituksessa usein käytettyjä.  Huomioitava on, että esimerkiksi yleiskaavatasolla voidaan käyttää irrallisena [AlueJotaKoskeeKehittamisperiaate](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/alueJotaKoskeeKehittamisperiaate)-koodia, mutta maakuntakaavatasolla kehittämisperiaatteet yleensä liittyvät johonkin toimintoon. Tästä esimerkkinä miten muodostetaan **Asumisen kehittämistarve**:

[AsumisenAlue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/AsumisenAlue) ja kehittämisperiaate määritellään [Lisätiedonlajin](linkki?)[Kehittämisperiaate](linkki?) avulla. 

Seuraavat kehittämisperiaatteet ovat myös käytössä maakuntakaavoissa

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/alueJotaKoskeeKehittamisperiaate>

1. 
{:toc}

## Yhdyskuntarakenteen laajenemissuunta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/yhdyskuntarakenteenLaajenemissuunta>

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoa, jotka sisältyy määrityshierarkioihin ```Aluevaraus``` ja ```Maakuntakaava``` ja joiden avulla voidaan kuvata laajenevan yhdyskuntarakenteen käyttötarkoitukset. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-geometria" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohteen" %}, johon liittyy Yhdyskuntarakenteen laajenemissuunta -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla pistemäinen tai viivamainen, ja sen tulee sijaita paikassa, josta yhdyskuntarakenne laajenee ```arvo```-attribuutin osoittamaan suuntaan.  
{% include common/clause_end.html %}


## Eheyttävä tai tiivistettävä alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/eheytettavaTaiTiivistettavaAlue>

{% include common/clause_start.html type="req" id="sp-yk/vaat-eheyttava-tiivistettava-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoa, jotka sisältyy määrityshierarkioihin ```Osa-alue``` ja ```Maakuntakaava``` ja joiden avulla voidaan kuvata käyttötarkoitus. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-geometria" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohteen" %}, johon liittyy Yhdyskuntarakenteen laajenemissuunta -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla aluemainen.  
{% include common/clause_end.html %}

## Kaupunki- tai kylakuvallisesti klehitettava alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/eheytettavaTaiTiivistettavaAlue>

{% include common/clause_start.html type="req" id="sp-yk/vaat-kaupunki-kylakuvallisesti-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoa, jotka sisältyy määrityshierarkioihin ```Osa-alue``` ja ```Maakuntakaava``` ja joiden avulla voidaan kuvata käyttötarkoitus. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-geometria" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohteen" %}, johon liittyy Yhdyskuntarakenteen laajenemissuunta -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla aluemainen tai pistemäinen.  
{% include common/clause_end.html %}
