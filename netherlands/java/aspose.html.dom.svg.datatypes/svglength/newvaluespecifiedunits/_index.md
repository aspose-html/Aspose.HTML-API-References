---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGLength methode. Reset de waarde als een getal met een bijbehorend eenheidstype, waardoor de waarden voor alle attributen van het object worden vervangen"
type: docs

url: /nl/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Reset de waarde als een getal met een bijbehorende unitType, waardoor de waarden voor alle attributen op het object worden vervangen.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| unitType | UInt16 | Het eenheidstype voor de waarde. |
| valueInSpecifiedUnits | Single | De nieuwe waarde.. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)Opgetreden wanneer unitType SVG_LENGTHTYPE_UNKNOWN is of geen geldige eenheidstype-constante is (een van de andere SVG_LENGTHTYPE_* constanten die op deze interface zijn gedefinieerd). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Opgeroepen wanneer de lengte overeenkomt met een alleen-lezen attribuut of wanneer het object zelf alleen-lezen is. |

### Zie ook

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
