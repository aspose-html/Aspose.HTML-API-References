---
title: "SVGAngle‑klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.datatypes.SVGAngle‑klass. SVGAngle‑gränssnittet motsvarar den grundläggande datatypen angle"
type: docs

url: /sv/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle-gränssnittet motsvarar den grundläggande datatypen vinkel.

```java
public class SVGAngle : SVGValueType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) Typen av värdet som specificeras av en av SVG_ANGLETYPE_*‑konstanterna som definierats på detta gränssnitt. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Behåll samma underliggande lagrade värde, men återställ den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Återställ värdet som ett tal med en associerad unitType, vilket ersätter värdena för alla attribut på objektet. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | Returnerar en sträng som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Enhetstypen sattes explicit till grader. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Enhetstypen är radianer. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Enhetstypen är radianer. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Enhetstypen är inte en av de fördefinierade enhetstyperna. Det är ogiltigt att försöka definiera ett nytt värde av denna typ eller att försöka byta ett befintligt värde till denna typ. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Ingen enhetstyp angavs (dvs. ett enhetslöst värde specificerades). För vinklar behandlas ett enhetslöst värde på samma sätt som om grader angavs. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
