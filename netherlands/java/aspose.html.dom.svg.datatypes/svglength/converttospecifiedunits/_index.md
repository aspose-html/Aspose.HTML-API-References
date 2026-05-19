---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGLength methode. Behoud dezelfde onderliggende opgeslagen waarde maar reset de opgeslagen eenheidsidentificator naar het opgegeven unitType. Objectattributen unitType, valueInSpecifiedUnits en valueAsString kunnen als gevolg van deze methode worden aangepast. Bijvoorbeeld, als de oorspronkelijke waarde 0,5 cm was en de methode werd aangeroepen om te converteren naar millimeters, dan zou unitType worden gewijzigd naar SVG_LENGTHTYPE_MM, valueInSpecifiedUnits zou worden gewijzigd naar de numerieke waarde 5 en valueAsString zou worden gewijzigd naar 5 mm."
type: docs

url: /nl/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Behoud dezelfde onderliggende opgeslagen waarde, maar reset de opgeslagen eenheididentificator naar de opgegeven unitType. Objectattributen unitType, valueInSpecifiedUnits en valueAsString kunnen worden gewijzigd als gevolg van deze methode. Bijvoorbeeld, als de oorspronkelijke waarde "0.5cm" was en de methode werd aangeroepen om naar millimeters te converteren, dan zou unitType worden gewijzigd naar SVG_LENGTHTYPE_MM, valueInSpecifiedUnits zou worden gewijzigd naar de numerieke waarde 5 en valueAsString zou worden gewijzigd naar "5mm".

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| unitType | UInt16 | Het eenheidstype om naartoe te schakelen (bijv. SVG_LENGTHTYPE_MM). |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Opgetreden als unitType SVG_LENGTHTYPE_UNKNOWN is of geen geldige eenheidstype-constante (een van de andere SVG_LENGTHTYPE_* constanten gedefinieerd op deze interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Opgetreden wanneer de lengte overeenkomt met een alleen-lezen attribuut of wanneer het object zelf alleen-lezen is. |

### Zie ook

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
