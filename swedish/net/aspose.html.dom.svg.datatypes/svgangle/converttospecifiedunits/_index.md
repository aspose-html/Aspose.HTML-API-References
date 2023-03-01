---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Aspose.HTML för .NET API Referens
description: SVGAngle metod. Bevara samma underliggande lagrade värde men återställ den lagrade enhetsidentifieraren till den givna unitType. Objektattribut unitType valueInSpecifiedUnits och valueAsString kan ändras som ett resultat av denna metod.
type: docs
weight: 50
url: /sv/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Bevara samma underliggande lagrade värde, men återställ den lagrade enhetsidentifieraren till den givna unitType. Objektattribut unitType, valueInSpecifiedUnits och valueAsString kan ändras som ett resultat av denna metod.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unitType | UInt16 | Enhetstypen att byta till (t.ex. SVG_ANGLETYPE_DEG). |

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Ökas om unitType är SVG_ANGLETYPE_UNKNOWN eller inte är en giltig enhetstypkonstant (en av de andra SVG_ANGLETYPE_*-konstanterna som definieras i detta gränssnitt). |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Höjs när vinkeln motsvarar ett skrivskyddat attribut eller när själva objektet är skrivskyddat. |

### Se även

* class [SVGAngle](../)
* namnutrymme [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* hopsättning [Aspose.HTML](../../../)


