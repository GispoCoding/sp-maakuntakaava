---
layout: "default"
description: ""
id: "kehittamisperiaatteet"
status: "Ehdotus"
---
# Kaavamääräyslajit - kehittämisperiaatteet
{:.no_toc}


## Yhteystarve

Yhteystarve voi olla jonkin kaavamääräyksen lisätiedonlajina. 

**Lisätiedonlaji: yhteystarve**

Maakuntakaavatasolla yhteystarve voi  liittyä myös johonkin toimintoon. Tästä esimerkkinä miten muodostetaan **Joukkoliikenteen kehittämistarve**:

[JoukkoliikenteenAlue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/JoukkoliikenteenAlue) ja kehittämisperiaate määritellään [Lisätiedonlajin](linkki?) [Yhteystarve](linkki?) avulla. 


## Kehittämisvyöhyke

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/Kehittamisvyöhyke>

Seuraavat maakuntakaavoissa usein käytetyt toiminnallisuudet voidaan kuvata [Kehittämisvyöhyke](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/kehittamisVyohyke) ```arvo```-attribuutin arvoina saa esiintyä mm. seuraavaa, myös muunlaiset arvot ovat sallittuja.
- Maaseudun kehittäminen
- Ekologinen kehittäminen
- Matkailun vetovoima-alue
- Kaupunkikehittäminen

## Yhdyskuntarakenteen laajenemissuunta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/yhdyskuntarakenteenLaajenemissuunta>

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoa, jotka sisältyy määrityshierarkioihin ```Aluevaraus``` ja ```Maakuntakaava``` ja joiden avulla voidaan kuvata laajenevan yhdyskuntarakenteen käyttötarkoitukset. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-geometria" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohteen" %}, johon liittyy Yhdyskuntarakenteen laajenemissuunta -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla pistemäinen tai viivamainen, ja sen tulee sijaita paikassa, josta yhdyskuntarakenne laajenee ```arvo```-attribuutin osoittamaan suuntaan.  
{% include common/clause_end.html %}

## Kaupunki- tai kylakuvallisesti kehitettava alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/kaupunkiTaiKylaKuvallisestiKehitettavaAlue>

{% include common/clause_start.html type="req" id="sp-yk/vaat-kaupunki-kylakuvallisesti-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoa, jotka sisältyy määrityshierarkioihin ```Maakuntakaava``` ja joiden avulla voidaan kuvata käyttötarkoitus. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-geometria" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohteen" %}, johon liittyy Kaupunki- tai kyläkuvallisesti kehitettävä alue -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla aluemainen tai pistemäinen.  
{% include common/clause_end.html %}
