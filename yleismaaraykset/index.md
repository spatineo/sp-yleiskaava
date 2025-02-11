---
layout: "default"
description: ""
id: "yleismaaraykset"
status: "Ehdotus"
---
# Kaavamääräyslajit - yleismääräykset
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/08>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.


## Yleismääräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0801>

{% include clause_start.html type="req" id="prof-yk/vaat-yleismaarays-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka kuvaa kaavamääräyksen. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-yleismaarays-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Yleiskaavan käyttö rakennusluvan myöntämisen perusteena
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0802>

Rakennuslupa rakennuksen rakentamiseen voidaan MRL:n [137 §:n](https://www.finlex.fi/fi/laki/ajantasa/1999/19990132#L19P137) 1 momentissa säädetyn estämättä myöntää, jos oikeusvaikutteisessa yleiskaavassa on erityisesti määrätty kaavan tai sen osan käyttämisestä rakennusluvan myöntämisen perusteena. Määräys ei voi koskea aluetta, jolla maankäytön ohjaustarve edellyttää asemakaavan laatimista. Edellytyksenä on lisäksi, että yleiskaava ohjaa riittävästi rakentamista ja muuta maankäyttöä kyseisellä alueella.

{% include clause_start.html type="req" id="prof-yk/vaat-yk-kaytto-rakennusluvan-perusteena-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolle kohdistuvan rakennusluvan myöntämisessä voidaan käyttää yleiskaavaa myöntämisen perusteena.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-yk-kaytto-rakennusluvan-perusteena-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-yk-kaytto-rakennusluvan-perusteena-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}