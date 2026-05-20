---
title: "SVGLength-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.datatypes.SVGLength-klass. SVGLength-gränssnittet motsvarar den grundläggande datatypen längd. Ett SVGLength-objekt kan betecknas som skrivskyddat, vilket betyder att försök att ändra objektet kommer att resultera i ett undantag som kastas enligt beskrivningen nedan."
type: docs

url: /sv/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

SVGLength‑gränssnittet motsvarar den grundläggande datatypen length. Ett SVGLength‑objekt kan markeras som skrivskyddat, vilket innebär att försök att ändra objektet kommer att resultera i ett undantag som kastas, enligt beskrivningen nedan.

```java
public class SVGLength : SVGValueType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) Typen av värdet som anges av en av SVG_LENGTHTYPE_*-konstanterna som definieras på detta gränssnitt. |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Behåll samma underliggande lagrade värde, men återställ den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod. Till exempel, om det ursprungliga värdet var "0.5cm" och metoden anropades för att konvertera till millimeter, så skulle unitType ändras till SVG_LENGTHTYPE_MM, valueInSpecifiedUnits ändras till det numeriska värdet 5 och valueAsString ändras till "5mm". |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Återställ värdet som ett tal med en associerad unitType, vilket ersätter värdena för alla attribut på objektet. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | Returnerar en sträng som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | Ett värde angavs med cm-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | Ett värde angavs med em-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | Ett värde angavs med ex-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | Ett värde angavs med in-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | Ett värde angavs med mm-enheterna som defineras i CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Ingen enhetstyp angavs (dvs. ett enhetslöst värde specificerades), vilket indikerar ett värde i användarenheter. |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | Ett värde angavs med pc-enheterna som definieras i CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Ett procentvärde angavs. |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | Ett värde angavs med pt-enheterna som defineras i CSS2. |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | Ett värde angavs med px-enheterna som defineras i CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Enhetstypen är inte en av de fördefinierade enhetstyperna. Det är ogiltigt att försöka definiera ett nytt värde av denna typ eller att försöka byta ett befintligt värde till denna typ. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
