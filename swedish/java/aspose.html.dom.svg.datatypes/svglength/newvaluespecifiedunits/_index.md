---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGLength-metod. Återställ värdet som ett tal med en associerad unitType och ersätt därmed värdena för alla attribut på objektet"
type: docs

url: /sv/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Återställ värdet som ett tal med en associerad unitType, vilket ersätter värdena för alla attribut på objektet.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unitType | UInt16 | Enhetstypen för värdet. |
| valueInSpecifiedUnits | Single | Det nya värdet.. |

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)Uppstår om unitType är SVG_LENGTHTYPE_UNKNOWN eller inte är en giltig enhetstypkonstant (en av de andra SVG_LENGTHTYPE_*-konstanterna som definieras på detta gränssnitt). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Utlöst när längden motsvarar ett skrivskyddat attribut eller när objektet självt är skrivskyddat. |

### Se även

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
