---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGAngle methode. Behoud dezelfde onderliggende opgeslagen waarde maar reset de opgeslagen eenheidsidentificator naar het opgegeven unitType. Objectattributen unitType, valueInSpecifiedUnits en valueAsString kunnen als gevolg van deze methode worden gewijzigd."
type: docs

url: /nl/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Behoud dezelfde onderliggende opgeslagen waarde, maar reset de opgeslagen eenheidsidentifier naar het opgegeven unitType. Objectattributen unitType, valueInSpecifiedUnits en valueAsString kunnen als gevolg van deze methode worden gewijzigd.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| unitType | UInt16 | Het eenheidstype om naar over te schakelen (bijv. SVG_ANGLETYPE_DEG). |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Opgegooid als unitType SVG_ANGLETYPE_UNKNOWN is of geen geldige eenheidstype-constante (een van de andere SVG_ANGLETYPE_* constanten die op deze interface zijn gedefinieerd). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Opgetreden wanneer de hoek overeenkomt met een alleen-lezen attribuut of wanneer het object zelf alleen-lezen is. |

### Zie ook

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
