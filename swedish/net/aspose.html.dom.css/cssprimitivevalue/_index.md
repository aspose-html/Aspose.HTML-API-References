---
title: Class CSSPrimitiveValue
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Css.CSSPrimitiveValue klass. CSSPrimitiveValuegränssnittet representerar ett enda CSSvärde. Detta gränssnitt kan användas för att bestämma värdet av en specifik stilegenskap som för närvarande är inställd i ett block eller för att ställa in en specifik stilegenskap explicit inom blocket. En instans av detta gränssnitt kan erhållas från metoden getPropertyCSSValue i CSSStyleDeclarationgränssnittet. Ett CSSPrimitiveValueobjekt förekommer endast i en kontext av en CSSegenskap.
type: docs
weight: 330
url: /sv/net/aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue-gränssnittet representerar ett enda CSS-värde. Detta gränssnitt kan användas för att bestämma värdet av en specifik stilegenskap som för närvarande är inställd i ett block eller för att ställa in en specifik stilegenskap explicit inom blocket. En instans av detta gränssnitt kan erhållas från metoden getPropertyCSSValue i CSSStyleDeclaration-gränssnittet. Ett CSSPrimitiveValue-objekt förekommer endast i en kontext av en CSS-egenskap.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | En strängrepresentation av det aktuella värdet. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | En kod som definierar typen av värdet. |
| [PrimitiveType](../../aspose.html.dom.css/cssprimitivevalue/primitivetype/) { get; } | Typen av värdet som definieras av konstanterna som anges ovan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Bestämmer om den angivnaObject är lika med denna instans. |
| abstract [GetCounterValue](../../aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Denna metod används för att få Räknarvärdet. Om detta CSS-värde inte innehåller ett räknarvärde, höjs ett DOMException. Modifiering av motsvarande stilegenskap kan uppnås med Counter-gränssnittet. |
| abstract [GetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Denna metod används för att få ett flytvärde i en specificerad enhet. Om detta CSS-värde inte innehåller ett flytande värde eller inte kan konverteras till den angivna enheten, höjs ett DOMException. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Returnerar en hash-kod för denna instans. |
| abstract [GetIntValue](../../aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Denna metod används för att få ett int-värde i en specificerad enhet. Om detta CSS-värde inte innehåller ett int-värde eller inte kan konverteras till den angivna enheten, höjs ett DOMException. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| abstract [GetRectValue](../../aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Denna metod används för att få Rect-värdet. Om detta CSS-värde inte innehåller ett rect-värde, höjs ett DOMException. Modifiering av motsvarande stilegenskap kan uppnås med Rect-gränssnittet. |
| abstract [GetRGBColorValue](../../aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Denna metod används för att få RGB-färgen. Om detta CSS-värde inte innehåller ett RGB-färgvärde höjs ett DOMException. Modifiering av motsvarande stilegenskap kan uppnås med RGBColor-gränssnittet. |
| abstract [GetStringValue](../../aspose.html.dom.css/cssprimitivevalue/getstringvalue/)() | Denna metod används för att få strängvärdet. Om CSS-värdet inte innehåller ett strängvärde höjs ett DOMException. |
| abstract [SetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | En metod för att ställa in flytvärdet med en specificerad enhet. Om egenskapen som är kopplad till detta värde inte kan acceptera den angivna enheten eller flytvärdet, kommer värdet att vara oförändrat och ett DOMException kommer att höjas. |
| abstract [SetIntValue](../../aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | En metod för att ställa in int-värdet med en specificerad enhet. Om egenskapen bifogad med detta värde inte kan acceptera den angivna enheten eller int-värdet, kommer värdet att vara oförändrat och ett DOMException kommer att höjas. |
| abstract [SetStringValue](../../aspose.html.dom.css/cssprimitivevalue/setstringvalue/)(ushort, string) | En metod för att ställa in strängvärdet med den angivna enheten. Om egenskapen kopplad till detta värde inte kan acceptera den angivna enheten eller strängvärdet, kommer värdet att vara oförändrat och ett DOMException kommer att höjas. |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [CSS_ATTR](../../aspose.html.dom.css/cssprimitivevalue/css_attr/) | Värdet är en attributfunktion. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_CH](../../aspose.html.dom.css/cssprimitivevalue/css_ch/) | Värdet är en längd (ch). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_CM](../../aspose.html.dom.css/cssprimitivevalue/css_cm/) | Värdet är en längd (cm). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_COUNTER](../../aspose.html.dom.css/cssprimitivevalue/css_counter/) | Värdet är en räknare eller räknare funktion. Värdet kan erhållas genom att använda metoden GetCounterValue. |
| const [CSS_DEG](../../aspose.html.dom.css/cssprimitivevalue/css_deg/) | Värdet är en vinkel (grader). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_DIMENSION](../../aspose.html.dom.css/cssprimitivevalue/css_dimension/) | Värdet är ett tal med en okänd dimension. Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_DPCM](../../aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | Värdet är en punkter per centimeter (dpcm). |
| const [CSS_DPI](../../aspose.html.dom.css/cssprimitivevalue/css_dpi/) | Värdet är en punkter per tum (dpi). |
| const [CSS_DPPX](../../aspose.html.dom.css/cssprimitivevalue/css_dppx/) | Värdet är en punkter per 'px'-enhet (dppx). |
| const [CSS_EMS](../../aspose.html.dom.css/cssprimitivevalue/css_ems/) | Värdet är en längd (ems). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_EXS](../../aspose.html.dom.css/cssprimitivevalue/css_exs/) | Värdet är en längd (exs). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_GRAD](../../aspose.html.dom.css/cssprimitivevalue/css_grad/) | Värdet är en vinkel (grad). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_HZ](../../aspose.html.dom.css/cssprimitivevalue/css_hz/) | Värdet är en frekvens (Hz). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_IDENT](../../aspose.html.dom.css/cssprimitivevalue/css_ident/) | Värdet är en identifierare. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_IN](../../aspose.html.dom.css/cssprimitivevalue/css_in/) | Värdet är en längd (in). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_KHZ](../../aspose.html.dom.css/cssprimitivevalue/css_khz/) | Värdet är en frekvens (kHz). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_MM](../../aspose.html.dom.css/cssprimitivevalue/css_mm/) | Värdet är en längd (mm). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_MS](../../aspose.html.dom.css/cssprimitivevalue/css_ms/) | Värdet är en tid (ms). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_NUMBER](../../aspose.html.dom.css/cssprimitivevalue/css_number/) | Värdet är ett enkelt tal. Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PC](../../aspose.html.dom.css/cssprimitivevalue/css_pc/) | Värdet är en längd (st). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.html.dom.css/cssprimitivevalue/css_percentage/) | Värdet är en procentsats. Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PT](../../aspose.html.dom.css/cssprimitivevalue/css_pt/) | Värdet är en längd (pt). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PX](../../aspose.html.dom.css/cssprimitivevalue/css_px/) | Värdet är en längd (px). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_RAD](../../aspose.html.dom.css/cssprimitivevalue/css_rad/) | Värdet är en vinkel (rad). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_RECT](../../aspose.html.dom.css/cssprimitivevalue/css_rect/) | Värdet är en rect-funktion. Värdet kan erhållas genom att använda metoden GetRectValue. |
| const [CSS_REM](../../aspose.html.dom.css/cssprimitivevalue/css_rem/) | Värdet är en längd (rem). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_RGBCOLOR](../../aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | Värdet är en RGB-färg. Värdet kan erhållas genom att använda metoden GetRGBColorValue. |
| const [CSS_S](../../aspose.html.dom.css/cssprimitivevalue/css_s/) | Värdet är en tid (s). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_STRING](../../aspose.html.dom.css/cssprimitivevalue/css_string/) | Värdet är en STRING. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_UNKNOWN](../../aspose.html.dom.css/cssprimitivevalue/css_unknown/) | Värdet är inte ett erkänt CSS2-värde. Värdet kan endast erhållas genom att använda attributet cssText. |
| const [CSS_URI](../../aspose.html.dom.css/cssprimitivevalue/css_uri/) | Värdet är en URI. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_VH](../../aspose.html.dom.css/cssprimitivevalue/css_vh/) | Värdet är en procentandel av hela visningsportens höjd. |
| const [CSS_VMAX](../../aspose.html.dom.css/cssprimitivevalue/css_vmax/) | Värdet är en procentandel av visningsportens bredd eller höjd, beroende på vilken som är störst. |
| const [CSS_VMIN](../../aspose.html.dom.css/cssprimitivevalue/css_vmin/) | Värdet är en procentandel av visningsportens bredd eller höjd, beroende på vilket som är minst. |
| const [CSS_VW](../../aspose.html.dom.css/cssprimitivevalue/css_vw/) | Värdet är en procentandel av hela visningsportens bredd. |

### Se även

* class [CSSValue](../cssvalue/)
* namnutrymme [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* hopsättning [Aspose.HTML](../../)


