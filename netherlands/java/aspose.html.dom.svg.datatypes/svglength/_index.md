---
title: "SVGLength Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.svg.datatypes.SVGLength klasse. De SVGLength interface komt overeen met het basistype lengte. Een SVGLength object kan als alleen-lezen worden aangemerkt, wat betekent dat pogingen om het object te wijzigen zullen resulteren in een uitzondering die hieronder wordt beschreven."
type: docs

url: /nl/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

De SVGLength-interface komt overeen met het basisgegevenstype lengte. Een SVGLength-object kan als alleen-lezen worden aangemerkt, wat betekent dat pogingen om het object te wijzigen zullen resulteren in een gegooide uitzondering, zoals hieronder beschreven.

```java
public class SVGLength : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) Het type van de waarde zoals gespecificeerd door een van de SVG_LENGTHTYPE_* constanten die op deze interface zijn gedefinieerd. |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Behoud dezelfde onderliggende opgeslagen waarde, maar reset de opgeslagen eenheididentificator naar de opgegeven unitType. Objectattributen unitType, valueInSpecifiedUnits en valueAsString kunnen als gevolg van deze methode worden gewijzigd. Bijvoorbeeld, als de oorspronkelijke waarde "0.5cm" was en de methode werd aangeroepen om naar millimeters te converteren, dan zou unitType worden gewijzigd naar SVG_LENGTHTYPE_MM, valueInSpecifiedUnits zou worden gewijzigd naar de numerieke waarde 5 en valueAsString zou worden gewijzigd naar "5mm". |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Vrijgeeft niet-beheerde en - optioneel - beheerde bronnen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Reset de waarde als een getal met een bijbehorende unitType, waardoor de waarden voor alle attributen op het object worden vervangen. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | Retourneert een String die dit exemplaar vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | Een waarde werd gespecificeerd met de cm-eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | Een waarde werd gespecificeerd met de em-eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | Een waarde werd gespecificeerd met de ex-eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | Een waarde werd gespecificeerd met de in-eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | Een waarde werd gespecificeerd met de mm-eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Er werd geen eenheidstype opgegeven (d.w.z. een eenheidsloze waarde werd gespecificeerd), wat een waarde in gebruikers-eenheden aangeeft. |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | Een waarde werd gespecificeerd met de pc-eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Er werd een procentuele waarde gespecificeerd. |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | Een waarde werd gespecificeerd met de pt-eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | Een waarde werd gespecificeerd met de px-eenheden gedefinieerd in CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Het eenheidstype behoort niet tot de vooraf gedefinieerde eenheidstypen. Het is ongeldig om te proberen een nieuwe waarde van dit type te definiëren of om te proberen een bestaande waarde naar dit type te wijzigen. |

### Zie ook

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
