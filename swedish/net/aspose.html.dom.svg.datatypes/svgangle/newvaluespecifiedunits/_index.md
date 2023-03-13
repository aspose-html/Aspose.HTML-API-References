---
title: SVGAngle.NewValueSpecifiedUnits
second_title: Aspose.HTML för .NET API Referens
description: SVGAngle metod. Återställ värdet som ett tal med en associerad unitType och ersätt därmed värdena för alla attribut på objektet.
type: docs
weight: 60
url: /sv/net/aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Återställ värdet som ett tal med en associerad unitType, och ersätt därmed värdena för alla attribut på objektet.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newUnitType | UInt16 | Enhetstypen för värdet (t.ex. SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Vinkelvärdet. |

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Ökas om unitType är SVG_ANGLETYPE_UNKNOWN eller inte är en giltig enhetstypkonstant (en av de andra SVG_ANGLETYPE_*-konstanterna som definieras i detta gränssnitt). |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Höjs när vinkeln motsvarar ett skrivskyddat attribut eller när själva objektet är skrivskyddat. |

### Se även

* class [SVGAngle](../)
* namnutrymme [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* hopsättning [Aspose.HTML](../../../)


