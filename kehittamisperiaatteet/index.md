---
layout: "default"
description: ""
id: "kehittamisperiaatteet"
status: "Ehdotus"
---
# Kaavamääräyslajit - kehittämisperiaatteet
{:.no_toc}

Kehittämisperiaatteet, kuten [Kehittämistarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/Kehittamistarve), [Yhteystarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/Yhteystarve), [Selvitystarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/Selvitystarve),  ovat maakuntakaavoituksessa usein käytettyjä.  Huomioitava on, että erikseen {% include common/clause_start.html type="req" id="sp-yk/kehittamisperiaatteet" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="kehittämisperiaatteet" %} asema- ja yleiskaavatasolla voidaan käyttää irrallisena AlueJotaKoskeeKehittamisperiaate-koodia, mutta maakuntakaavatasolla kehittämisperiaatteet yleensä liittyvät johonkin toimintoon (esim. AsumisenAlue) ja kehittämisperiaate määritellään Lisätiedonlajin avulla (esim. Kehittämistarve) = Asumisen kehittämistarve



**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/alueJotaKoskeeKehittamisperiaate>

1. 
{:toc}

## Yhdyskuntarakenteen laajenemissuunta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/yhdyskuntarakenteenLaajenemissuunta>

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoa, jotka sisältyy määrityshierarkioihin ```Aluevaraus``` ja ```Yleiskaava``` ja joiden avulla voidaan kuvata laajenevan yhdyskuntarakenteen käyttötarkoitukset. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-geometria" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohteen" %}, johon liittyy Yhdyskuntarakenteen laajenemissuunta -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla pistemäinen, ja sen tulee sijaita paikassa, josta yhdyskuntarakenne laajenee ```arvo```-attribuutin osoittamaan suuntaan.  
{% include common/clause_end.html %}

