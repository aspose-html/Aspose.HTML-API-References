---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGAngle-metoden. Återställer värdet som ett tal med en associerad unitType och ersätter därmed värdena för alla attribut på objektet"
type: docs

url: /sv/java/com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Återställ värdet som ett tal med en associerad unitType, vilket ersätter värdena för alla attribut på objektet.

```java
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newUnitType | UInt16 | Enhetstypen för värdet (t.ex. SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Vinkelvärdet. |

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Utlöst om unitType är SVG_ANGLETYPE_UNKNOWN eller inte en giltig enhetstypkonstant (en av de andra SVG_ANGLETYPE_*-konstanterna som definieras på detta gränssnitt). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Uppstått när vinkeln motsvarar ett skrivskyddat attribut eller när objektet självt är skrivskyddat. |

### Se även

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
