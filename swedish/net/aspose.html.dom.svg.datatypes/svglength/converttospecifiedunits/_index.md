---
title: SVGLength.ConvertToSpecifiedUnits
second_title: Aspose.HTML för .NET API Referens
description: SVGLength metod. Bevara samma underliggande lagrade värde men återställ den lagrade enhetsidentifieraren till den givna unitType. Objektattributen unitType valueInSpecifiedUnits och valueAsString kan ändras som ett resultat av den här metoden. Till exempel om det ursprungliga värdet var 05 cm och metoden anropades för att konvertera till millimeter skulle unitType ändras till SVG_LENGTHTYPE_MM valueInSpecifiedUnits skulle ändras till det numeriska värdet 5 och valueAsString skulle ändras till 5mm.
type: docs
weight: 50
url: /sv/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Bevara samma underliggande lagrade värde, men återställ den lagrade enhetsidentifieraren till den givna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan ändras som ett resultat av den här metoden. Till exempel, om det ursprungliga värdet var "0,5 cm" och metoden anropades för att konvertera till millimeter, skulle unitType ändras till SVG_LENGTHTYPE_MM, valueInSpecifiedUnits skulle ändras till det numeriska värdet 5 och valueAsString skulle ändras till "5mm".

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unitType | UInt16 | Enhetstypen att byta till (t.ex. SVG_LENGTHTYPE_MM). |

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Ökas om unitType är SVG_LENGTHTYPE_UNKNOWN eller inte är en giltig enhetstypkonstant (en av de andra SVG_LENGTHTYPE_*-konstanterna som definieras i detta gränssnitt). |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Höjs när längden motsvarar ett skrivskyddat attribut eller när själva objektet är skrivskyddat. |

### Se även

* class [SVGLength](../)
* namnutrymme [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* hopsättning [Aspose.HTML](../../../)


