---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGAngle-methode. Reset de waarde als een getal met een bijbehorend unitType, waardoor de waarden voor alle attributen op het object worden vervangen"
type: docs

url: /nl/java/com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Reset de waarde als een getal met een bijbehorend unitType, waardoor de waarden voor alle attributen van het object worden vervangen.

```java
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newUnitType | UInt16 | Het eenheidstype voor de waarde (bijv., SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | De hoekwaarde. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Opgegooid als unitType SVG_ANGLETYPE_UNKNOWN is of geen geldige eenheidstype-constante (een van de andere SVG_ANGLETYPE_* constanten die op deze interface zijn gedefinieerd). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Opgetreden wanneer de hoek overeenkomt met een alleen-lezen attribuut of wanneer het object zelf alleen-lezen is. |

### Zie ook

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
