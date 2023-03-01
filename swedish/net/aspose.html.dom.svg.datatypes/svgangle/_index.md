---
title: Class SVGAngle
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Svg.DataTypes.SVGAngle klass. SVGAnglegränssnittet motsvarar vinkelns grundläggande datatyp.
type: docs
weight: 1060
url: /sv/net/aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle-gränssnittet motsvarar vinkelns grundläggande datatyp.

```csharp
public class SVGAngle : SVGValueType
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svgangle/unittype/) { get; } | Typen av värdet som specificeras av en av SVG_ANGLETYPE_*-konstanterna som definieras i detta gränssnitt. |
| [Value](../../aspose.html.dom.svg.datatypes/svgangle/value/) { get; set; } | Vinkelvärdet som ett flyttalsvärde, i grader. Om du ställer in det här attributet kommer valueInSpecifiedUnits och valueAsString att uppdateras automatiskt för att återspegla denna inställning. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svgangle/valueasstring/) { get; set; } | Vinkelvärdet som ett strängvärde, i enheterna uttryckta av unitType. Om du ställer in detta attribut kommer värde, valueInSpecifiedUnits och unitType att uppdateras automatiskt för att återspegla denna inställning. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | Vinkelvärdet som ett flyttalsvärde, i enheterna uttryckta av unitType. Om du ställer in detta attribut kommer värde och valueAsString att uppdateras automatiskt för att återspegla denna inställning. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Bevara samma underliggande lagrade värde, men återställ den lagrade enhetsidentifieraren till den givna unitType. Objektattribut unitType, valueInSpecifiedUnits och valueAsString kan ändras som ett resultat av denna metod. |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Återställ värdet som ett tal med en associerad unitType, och ersätt därmed värdena för alla attribut på objektet. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgangle/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Enhetstypen var uttryckligen inställd på grader. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Enhetstypen är radianer. |
| const [SVG_ANGLETYPE_RAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Enhetstypen är radianer. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Enhetstypen är inte en av fördefinierade enhetstyper. Det är ogiltigt att försöka definiera ett nytt värde av denna typ eller att försöka ändra ett befintligt värde till denna typ. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Ingen enhetstyp angavs (dvs ett värde utan enhet angavs). För vinklar behandlas ett enhetslöst värde på samma sätt som om grader angavs. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* namnutrymme [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* hopsättning [Aspose.HTML](../../)


