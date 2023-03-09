---
layout: "default"
description: ""
id: "suureet"
status: "Ehdotus"
---

# Kaavamääräykset - suureet
{:.no_toc}

<!-- Ainoastaan tuulivoimaloiden määrä tällä hetkellä tiedossa 03/2023-->

1. 
{:toc}

Suure-tyyppisillä kaavamääräyksillä tarkoitetaan tässä [Kaavamääräyslaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/)-koodiston koodeja, jotka sisältyvät määrityshierarkiaan ```Suure```.

{% include common/clause_start.html type="req" id="sp-mk/vaat-arvot" %}
Tyypiltään suuremaisille kaavamääräyksille on ```arvo```-attribuutin arvona annettava **täsmälleen yksi** {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %}.
{% include common/clause_end.html %}

## Tuulivoimaloiden määrä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/tuulivoimaloidenMaara>

{% include common/clause_start.html type="req" id="sp-yk/vaat-tuulivoimaloiden-maara-arvot" %}
```arvo```-attribuutin arvona saa esiintyä joko yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} jotka kertovat tuulivoimaloiden enimmäismäärän sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#integer" title="Integer" %}-rajapinta. Yksikköjä ei käytetä. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}
