---
title: "CSSPrimitiveValue-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.CSSPrimitiveValue-klass. CSSPrimitiveValue‑gränssnittet ärver från CSSValue‑gränssnittet och representerar det aktuella beräknade värdet av en CSS‑egenskap."
type: docs

url: /sv/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue‑gränssnittet härstammar från CSSValue‑gränssnittet och representerar det aktuella beräknade värdet för en CSS‑egenskap.

Obs: Detta gränssnitt var en del av ett försök att skapa en typad CSS‑objektmodell. Försöket har övergetts, och de flesta webbläsare implementerar det inte.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | cssText‑egenskapen för [`CSSValue`](../cssvalue/)‑gränssnittet representerar det aktuella beräknade CSS‑egenskapsvärdet. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) En kod som definierar värdets typ. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) Typen av värdet enligt de konstanter som specificerats ovan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Avgör om det angivna objektet är lika med denna instans. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Denna metod används för att hämta Counter‑värdet. Om detta CSS‑värde inte innehåller ett counter‑värde kastas ett DOMException. Modifiering av den motsvarande stil‑egenskapen kan uppnås med Counter‑gränssnittet. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Denna metod används för att hämta ett flyttalvärde i en specificerad enhet. Om detta CSS-värde inte innehåller ett flyttalvärde eller inte kan konverteras till den specificerade enheten, kastas ett DOMException. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Returnerar en hashkod för detta objekt. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Denna metod används för att hämta ett heltalsvärde i en specificerad enhet. Om detta CSS-värde inte innehåller ett heltalsvärde eller inte kan konverteras till den specificerade enheten, kastas ett DOMException. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Denna metod används för att hämta ECMAScript‑objekttypen. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Denna metod används för att hämta Rect-värdet. Om detta CSS-värde inte innehåller ett rect-värde, kastas ett DOMException. Ändring av motsvarande stil-egenskap kan göras med hjälp av Rect-gränssnittet. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Denna metod används för att hämta RGB-färgen. Om detta CSS-värde inte innehåller ett RGB-färgvärde, kastas ett DOMException. Ändring av motsvarande stil-egenskap kan göras med hjälp av RGBColor-gränssnittet. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | Denna metod används för att hämta String-värdet. Om CSS-värdet inte innehåller ett String-värde, kastas ett DOMException. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | En metod för att sätta flyttalvärdet med en specificerad enhet. Om egenskapen som är kopplad till detta värde inte kan acceptera den specificerade enheten eller flyttalvärdet, förblir värdet oförändrat och ett DOMException kastas. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | En metod för att sätta heltalsvärdet med en specificerad enhet. Om egenskapen som är kopplad till detta värde inte kan acceptera den specificerade enheten eller heltalsvärdet, förblir värdet oförändrat och ett DOMException kastas. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | En metod för att sätta String-värdet med den specificerade enheten. Om egenskapen som är kopplad till detta värde inte kan acceptera den specificerade enheten eller String-värdet, förblir värdet oförändrat och ett DOMException kastas. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Returnerar en sträng som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | Värdet är en attributfunktion. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | Värdet är en längd (ch). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | Värdet är en längd (cm). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | Värdet är en counter- eller counters-funktion. Värdet kan erhållas genom att använda metoden GetCounterValue. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | Värdet är en vinkel (deg). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | Värdet är ett tal med en okänd dimension. Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | Värdet är punkter per centimeter (dpcm). |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | Värdet är punkter per tum (dpi). |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | Värdet är punkter per ‘px’-enhet (dppx). |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | Värdet är en längd (ems). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | Värdet är en längd (exs). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | Värdet är en vinkel (grad). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | Värdet är en frekvens (Hz). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | Värdet är en identifierare. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | Värdet är en längd (in). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | Värdet är en frekvens (kHz). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | Värdet är en längd (mm). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | Värdet är en tid (ms). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | Värdet är ett enkelt tal. Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | Värdet är en längd (pc). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | Värdet är en procentsats. Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | Värdet är en längd (pt). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | Värdet är en längd (px). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | Värdet är en vinkel (rad). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | Värdet är en rect-funktion. Värdet kan erhållas genom att använda metoden GetRectValue. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | Värdet är en längd (rem). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | Värdet är en RGB-färg. Värdet kan erhållas genom att använda metoden GetRGBColorValue. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | Värdet är en tid (s). Värdet kan erhållas genom att använda metoden getFloatValue. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | Värdet är en STRING. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | Värdet är inte ett känt CSS2‑värde. Värdet kan endast erhållas genom att använda attributet cssText. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | Värdet är en URI. Värdet kan erhållas genom att använda metoden getStringValue. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | Värdet är en procentsats av hela viewport‑höjden. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | Värdet är en procentsats av viewport‑bredden eller -höjden, beroende på vilken som är störst. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | Värdet är en procentsats av viewport‑bredden eller -höjden, beroende på vilken som är minst. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | Värdet är en procentsats av hela viewport‑bredden. |

### Se även

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
