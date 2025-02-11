---
layout: "default"
description: ""
id: "alueen-osan-erityisominaisuudet"
status: "Ehdotus"
---
# Kaavamääräyslajit - alueen osan erityisominaisuudet
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/06>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

1. 
{:toc}

## Erityisharkinta-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0601>

{% include clause_start.html type="req" id="prof-yk/vaat-erityisharkinta-alue-maar" %}
Ilmaisee, että kaavakohteen alueella ei ole rakentamista ohjaavaa kaavaa, mutta rakennushankkeen sijoittumista on syytä erityisesti harkita ennen luvan myöntämistä.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-erityisharkinta-alue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.  Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-erityisharkinta-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Kehittämisalue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0602>

{% include clause_start.html type="req" id="prof-yk/vaat-kehittamisalue-maar" %}
Ilmaisee, että kaavakohde kuvaa tunnistettua erityisaluetta, jossa erityiset kehittämis- tai toteuttamistoimenpiteet ovat tarpeen. Kehittämisalue-status on voimassa määräajan.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-kehittamisalue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä joko
* yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo), joka kuvaa sen kaavan hyväksymisestä alkavan ajanjakson pituuden, jona kehittämisalue-status on voimassa. Numeerisen arvon  on toteutettava [Integer](../../looginenmalli/dokumentaatio/#integer)-rajapinta. Yksikkönä vuosi (```v```), tai kuukausi (```kk```) tai
* yksi [Ajanhetkiarvo](../../looginenmalli/dokumentaatio/#ajanhetkiarvo), joka kuvaa päivämäärän, johon saakka kehittämisalue-status on voimassa.

Lisäksi ```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.

Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-kehittamisalue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Vaara-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0603>

{% include clause_start.html type="req" id="prof-yk/vaat-vaara-alue-maar" %}
Ilmaisee, että kaavakohteen kuvaa alueen, joilla liikkuminen on turvallisuussyistä rajoitettu tai sitä on tarkoitus rajoittaa.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-vaara-alue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), jotka kuvaavat vaaran luonteen ja sen vaikutukset alueen käyttömahdollisuuksiin.  Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-vaara-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Suojavyöhyke
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0604>

{% include clause_start.html type="req" id="prof-yk/vaat-suojavohyke-maar" %}
Ilmaisee, että kaavakohteen kuvaa alueen, jolla alueiden käyttöä on läheisen vaara-alueen tai muun mpäristöönsä käyttörajoituksia aiheuttavan toiminnan luonteen vuoksi rajoitettava.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-suojavohyke-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), jotka kuvaavat alueiden käytön reunaehtoja tai suojavaikutuksen lisäämistä.  Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-suojavohyke-lisatiedot" %}
* ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), jonka laji on [Poisluettava käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_YK/code/04), ja jonka ```arvo```-attribuutin arvoina on yksi tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat koodiston KaavamääraysLaji koodin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/01) alakoodeihin. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

## Suunnittelutarvealue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0605>

{% include clause_start.html type="req" id="prof-yk/vaat-suunnittelutarvealue-maar" %}
Ilmaisee, että kaavakohde kuvaa aluetta, joilla on odotettavissa suunnittelua edellyttävää yhdyskuntakehitystä tai jolla erityisten ympäristöarvojen tai ympäristöhaittojen takia on tarpeen suunnitella maankäyttöä.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-suunnittelutarvealue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä joko
* yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo), joka kuvaa sen kaavan hyväksymisestä alkavan ajanjakson pituuden, jona suunnittelutarvealue-status on voimassa. Numeerisen arvon  on toteutettava [Integer](../../looginenmalli/dokumentaatio/#integer)-rajapinta. Yksikkönä vuosi (```v```), tai kuukausi (```kk```) tai
* yksi [Ajanhetkiarvo](../../looginenmalli/dokumentaatio/#ajanhetkiarvo), joka kuvaa päivämäärän, johon saakka suunnittelutarvealue-status on voimassa.

Lisäksi ```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.

Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-suunnittelutarvealue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}


## Reservialue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0606>

{% include clause_start.html type="req" id="prof-yk/vaat-reservialue-maar" %}
Ilmaisee, että kaavakohde kuvaa aluetta, joka on alustavasti tai ehdollisesti varattu tiettyyn käyttötarkoitukseen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-suunnittelutarvealue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä seuraavat:
 * Nolla tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), joka viittaa KaavamääraysLaji-koodiston koodin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/01) siihen alakoodiin, johon käyttöön alue on alustavasti tai ehdollisesti varattu.
 * Nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-suunnittelutarvealue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Muu alueen osan erityisominaisuus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0607>

{% include clause_start.html type="req" id="prof-yk/vaat-muu-alueen-osan-erityisominaisuus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka kuvaa kaavamääräyksen.  Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-muu-alueen-osan-erityisominaisuus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}