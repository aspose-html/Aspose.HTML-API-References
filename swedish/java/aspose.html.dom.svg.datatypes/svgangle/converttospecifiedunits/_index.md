---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGAngle method. Bevara samma underliggande lagrade värde men återställ den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod."
type: docs

url: /sv/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Behåll samma underliggande lagrade värde, men återställ den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unitType | UInt16 | Enhetstypen att byta till (t.ex. SVG_ANGLETYPE_DEG). |

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Utlöst om unitType är SVG_ANGLETYPE_UNKNOWN eller inte en giltig enhetstypkonstant (en av de andra SVG_ANGLETYPE_*-konstanterna som definieras på detta gränssnitt). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Uppstått när vinkeln motsvarar ett skrivskyddat attribut eller när objektet självt är skrivskyddat. |

### Se även

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
