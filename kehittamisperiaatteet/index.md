---
layout: "default"
description: ""
id: "kehittamisperiaatteet"
status: "Ehdotus"
---
# Kaavamääräyslajit - kehittämisperiaatteet
{:.no_toc}


## Kehittämistarve, yhteystarve ja selvitystarve lisätiedon lajina

Kehittämistarve, yhteystarve ja selvitystarve voivat olla jonkin kaavamääräyksen lisätiedonlajina. 

### Toiminto, jolla kehittämistarve lisätiedonlajina

**Lisätiedonlaji: kehittämistarve**

Maakuntakaavatasolla kehittämisperiaatteet voivat liittyä myös johonkin toimintoon. Tästä esimerkkinä miten muodostetaan **Asumisen kehittämistarve**:

[AsumisenAlue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/AsumisenAlue) ja kehittämisperiaate määritellään [Lisätiedonlajin](linkki?) [Kehittämisperiaate](linkki?) avulla. 

### Toiminto, jolla yhteystarve lisätiedonlajina

**Lisätiedonlaji: yhteystarve**

Maakuntakaavatasolla yhteystarve voi  liittyä myös johonkin toimintoon. Tästä esimerkkinä miten muodostetaan **Joukkoliikenteen kehittämistarve**:

[JoukkoliikenteenAlue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/JoukkoliikenteenAlue) ja kehittämisperiaate määritellään [Lisätiedonlajin](linkki?) [Yhteystarve](linkki?) avulla. 


## Alue, jota koskee kehittämisperiaate

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/alueJotaKoskeeKehittamisperiaate>

Esimerkkejä:
- [AlueJotaKoskeeKehittamisperiaate](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/alueJotaKoskeeKehittamisperiaate) ja [Lisätiedonlajin](linkki?)  [Eheyttävä tai tiivistettävä alue](linkki?).

Seuraavat maakuntakaavoissa usein käytetyt toiminnallisuudet voidaan kuvata [AlueJotaKoskeeKehittamisperiaate](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/alueJotaKoskeeKehittamisperiaate) antamalla niille TekstiArvo 
- Maaseudun kehittäminen
- Ekologinen kehittäminen
- Matkailun vetovoima-alue
- Kaupunkikehittäminen
- Myös muita TekstiArvoja sallitaan 

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
