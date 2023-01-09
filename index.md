---
layout: "default"
description: ""
id: "johdanto"
status: "Ehdotus"
---
# Kaavatietomallin soveltamisprofiili maakuntakaava-aineistoille
{:.no_toc}

Tämän dokumentin vaatimukset ja suositukset muodostavat Kaavatietomallin loogisen tietomallin soveltamisprofiilin maakuntakaava-aineistoille. Soveltamisprofiili kuvaa ne rajoitukset ja lisävaatimukset, joita tulee noudattaa Kaavatietomallin {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/uml/doc/" title="UML-kielisen kuvauksen" %} ja sen {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/" title="sanallisen dokumentaation" %} soveltamisessa maakuntakaavan tietoaineistojen kuvaamiseen.

Tämän muodollisen dokumentin tietoja täydentää [Maakuntakaavan kaavamääräysopas]() **onko tällaista opasta? vai visuohjeistus tähän?**, joka sisältää käytännön esimerkkejä Kaavatietomallin soveltamisesta maakuntakaavoituksen kaavoitusratkaisuihin.

{% include common/clause_start.html type="req" id="prof-mk/vaat-maakuntakaava-aineisto-maar" %} **tarkista onko** 
Kaavatietomallin mukainen maakuntakaava-aineisto koostuu {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaava" title="Kaava" %}-luokan instansseista, joiden ```laji```-attribuutin arvo on jokin Kaavalajit-koodiston koodin [Maakuntakaava](http://uri.suomi.fi/codelist/rytj/RY_Kaavalaji/code/1) {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeista" %}, sekä näihin instansseihin Kaavatietomallin mukaisesti liittyvistä muiden luokkien instansseista.
{% include common/clause_end.html %}