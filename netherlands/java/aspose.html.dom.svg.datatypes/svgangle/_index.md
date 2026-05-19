---
title: "SVGAngle Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.svg.datatypes.SVGAngle klasse. De SVGAngle-interface komt overeen met het basistype hoek"
type: docs

url: /nl/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

De SVGAngle interface komt overeen met het basisgegevenstype hoek.

```java
public class SVGAngle : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) Het type van de waarde zoals gespecificeerd door een van de SVG_ANGLETYPE_* constanten die op deze interface zijn gedefinieerd. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Behoud dezelfde onderliggende opgeslagen waarde, maar reset de opgeslagen eenheidsidentifier naar het opgegeven unitType. Objectattributen unitType, valueInSpecifiedUnits en valueAsString kunnen als gevolg van deze methode worden gewijzigd. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Vrijgeeft onbeheerste en - optioneel - beheerde bronnen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Reset de waarde als een getal met een bijbehorend unitType, waardoor de waarden voor alle attributen van het object worden vervangen. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Het eenheidstype werd expliciet ingesteld op graden. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Het eenheidstype is radialen. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Het eenheidstype is radialen. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Het eenheidstype is niet een van de vooraf gedefinieerde eenheidstypen. Het is ongeldig om te proberen een nieuwe waarde van dit type te definiëren of om een bestaande waarde naar dit type te wijzigen. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Er werd geen eenheidstype opgegeven (d.w.z. een eenheidsloze waarde werd gespecificeerd). Voor hoeken wordt een eenheidsloze waarde op dezelfde manier behandeld alsof graden waren opgegeven. |

### Zie ook

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
