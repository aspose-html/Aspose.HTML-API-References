---
title: SVGLength.NewValueSpecifiedUnits
second_title: Aspose.HTML för .NET API Referens
description: SVGLength metod. Återställ värdet som ett tal med en associerad unitType och ersätt därmed värdena för alla attribut på objektet.
type: docs
weight: 60
url: /sv/net/aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Återställ värdet som ett tal med en associerad unitType, och ersätt därmed värdena för alla attribut på objektet.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unitType | UInt16 | Enhetstypen för värdet. |
| valueInSpecifiedUnits | Single | Det nya värdet.. |

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Ökas om unitType är SVG_LENGTHTYPE_UNKNOWN eller inte är en giltig enhetstypkonstant (en av de andra SVG_LENGTHTYPE_*-konstanterna som definieras i detta gränssnitt). |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Höjs när längden motsvarar ett skrivskyddat attribut eller när själva objektet är skrivskyddat. |

### Se även

* class [SVGLength](../)
* namnutrymme [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* hopsättning [Aspose.HTML](../../../)


