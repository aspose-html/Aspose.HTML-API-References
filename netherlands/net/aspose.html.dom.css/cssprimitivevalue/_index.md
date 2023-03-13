---
title: Class CSSPrimitiveValue
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Css.CSSPrimitiveValue klas. De interface CSSPrimitiveValue vertegenwoordigt een enkele CSSwaarde. Deze interface kan worden gebruikt om de waarde te bepalen van een specifieke stijleigenschap die momenteel in een blok is ingesteld of om een specifieke stijleigenschap expliciet binnen het blok in te stellen. Een exemplaar van deze interface kan worden verkregen via de getPropertyCSSValuemethode van de CSSStyleDeclarationinterface. Een CSSPrimitiveValueobject komt alleen voor in een context van een CSSeigenschap.
type: docs
weight: 330
url: /nl/net/aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

De interface CSSPrimitiveValue vertegenwoordigt een enkele CSS-waarde. Deze interface kan worden gebruikt om de waarde te bepalen van een specifieke stijleigenschap die momenteel in een blok is ingesteld of om een specifieke stijleigenschap expliciet binnen het blok in te stellen. Een exemplaar van deze interface kan worden verkregen via de getPropertyCSSValue-methode van de CSSStyleDeclaration-interface. Een CSSPrimitiveValue-object komt alleen voor in een context van een CSS-eigenschap.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Een tekenreeksrepresentatie van de huidige waarde. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | Een code die het type waarde definieert. |
| [PrimitiveType](../../aspose.html.dom.css/cssprimitivevalue/primitivetype/) { get; } | Het type waarde zoals gedefinieerd door de hierboven gespecificeerde constanten. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Bepaalt of de opgegevenObject is gelijk aan deze instantie. |
| abstract [GetCounterValue](../../aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Deze methode wordt gebruikt om de tellerwaarde te krijgen. Als deze CSS-waarde geen tellerwaarde bevat, wordt een DOMException gegenereerd. Wijziging van de overeenkomstige stijleigenschap kan worden bereikt met behulp van de tellerinterface. |
| abstract [GetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Deze methode wordt gebruikt om een float-waarde in een opgegeven eenheid te krijgen. Als deze CSS-waarde geen float-waarde bevat of niet kan worden geconverteerd naar de opgegeven eenheid, wordt een DOMException gegenereerd. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Retourneert een hash-code voor deze instantie. |
| abstract [GetIntValue](../../aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Deze methode wordt gebruikt om een int-waarde in een gespecificeerde eenheid te verkrijgen. Als deze CSS-waarde geen int-waarde bevat of niet kan worden geconverteerd naar de opgegeven eenheid, wordt een DOMException gegenereerd. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| abstract [GetRectValue](../../aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Deze methode wordt gebruikt om de Rect-waarde te verkrijgen. Als deze CSS-waarde geen rect-waarde bevat, wordt een DOMException gegenereerd. Wijziging van de overeenkomstige stijleigenschap kan worden bereikt met behulp van de Rect-interface. |
| abstract [GetRGBColorValue](../../aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Deze methode wordt gebruikt om de RGB-kleur te krijgen. Als deze CSS-waarde geen RGB-kleurwaarde bevat, wordt er een DOMException gegenereerd. Wijziging van de overeenkomstige stijleigenschap kan worden bereikt met behulp van de RGBColor-interface. |
| abstract [GetStringValue](../../aspose.html.dom.css/cssprimitivevalue/getstringvalue/)() | Deze methode wordt gebruikt om de tekenreekswaarde te verkrijgen. Als de CSS-waarde geen tekenreekswaarde bevat, wordt een DOMException gegenereerd. |
| abstract [SetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Een methode om de float-waarde in te stellen met een gespecificeerde eenheid. Als de eigenschap die aan deze waarde is gekoppeld, de opgegeven eenheid of de float-waarde niet kan accepteren, blijft de waarde ongewijzigd en wordt er een DOMException verhoogd. |
| abstract [SetIntValue](../../aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Een methode om de int-waarde in te stellen met een gespecificeerde eenheid. Als de eigenschap die aan deze waarde is gekoppeld de opgegeven eenheid of de int-waarde niet kan accepteren, blijft de waarde ongewijzigd en wordt er een DOMException gegenereerd. |
| abstract [SetStringValue](../../aspose.html.dom.css/cssprimitivevalue/setstringvalue/)(ushort, string) | Een methode om de tekenreekswaarde in te stellen met de opgegeven eenheid. Als de eigenschap die aan deze waarde is gekoppeld de opgegeven eenheid of tekenreekswaarde niet kan accepteren, blijft de waarde ongewijzigd en wordt er een DOMException gegenereerd. |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [CSS_ATTR](../../aspose.html.dom.css/cssprimitivevalue/css_attr/) | De waarde is een attribuutfunctie. De waarde kan worden verkregen met behulp van de methode getStringValue. |
| const [CSS_CH](../../aspose.html.dom.css/cssprimitivevalue/css_ch/) | De waarde is een lengte (ch). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_CM](../../aspose.html.dom.css/cssprimitivevalue/css_cm/) | De waarde is een lengte (cm). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_COUNTER](../../aspose.html.dom.css/cssprimitivevalue/css_counter/) | De waarde is een teller of tellersfunctie. De waarde kan worden verkregen met behulp van de methode GetCounterValue. |
| const [CSS_DEG](../../aspose.html.dom.css/cssprimitivevalue/css_deg/) | De waarde is een hoek (graden). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_DIMENSION](../../aspose.html.dom.css/cssprimitivevalue/css_dimension/) | De waarde is een getal met een onbekende dimensie. De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_DPCM](../../aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | De waarde is een aantal punten per centimeter (dpcm). |
| const [CSS_DPI](../../aspose.html.dom.css/cssprimitivevalue/css_dpi/) | De waarde is een aantal dots per inch (dpi). |
| const [CSS_DPPX](../../aspose.html.dom.css/cssprimitivevalue/css_dppx/) | De waarde is een aantal punten per 'px'-eenheid (dppx). |
| const [CSS_EMS](../../aspose.html.dom.css/cssprimitivevalue/css_ems/) | De waarde is een lengte (ems). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_EXS](../../aspose.html.dom.css/cssprimitivevalue/css_exs/) | De waarde is een lengte (exs). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_GRAD](../../aspose.html.dom.css/cssprimitivevalue/css_grad/) | De waarde is een hoek (gradiënt). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_HZ](../../aspose.html.dom.css/cssprimitivevalue/css_hz/) | De waarde is een frequentie (Hz). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_IDENT](../../aspose.html.dom.css/cssprimitivevalue/css_ident/) | De waarde is een identifier. De waarde kan worden verkregen met behulp van de methode getStringValue. |
| const [CSS_IN](../../aspose.html.dom.css/cssprimitivevalue/css_in/) | De waarde is een lengte (in). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_KHZ](../../aspose.html.dom.css/cssprimitivevalue/css_khz/) | De waarde is een frequentie (kHz). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_MM](../../aspose.html.dom.css/cssprimitivevalue/css_mm/) | De waarde is een lengte (mm). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_MS](../../aspose.html.dom.css/cssprimitivevalue/css_ms/) | De waarde is een tijd (ms). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_NUMBER](../../aspose.html.dom.css/cssprimitivevalue/css_number/) | De waarde is een eenvoudig getal. De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_PC](../../aspose.html.dom.css/cssprimitivevalue/css_pc/) | De waarde is een lengte (pc). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.html.dom.css/cssprimitivevalue/css_percentage/) | De waarde is een percentage. De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_PT](../../aspose.html.dom.css/cssprimitivevalue/css_pt/) | De waarde is een lengte (pt). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_PX](../../aspose.html.dom.css/cssprimitivevalue/css_px/) | De waarde is een lengte (px). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_RAD](../../aspose.html.dom.css/cssprimitivevalue/css_rad/) | De waarde is een hoek (rad). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_RECT](../../aspose.html.dom.css/cssprimitivevalue/css_rect/) | De waarde is een rect-functie. De waarde kan worden verkregen met behulp van de methode GetRectValue. |
| const [CSS_REM](../../aspose.html.dom.css/cssprimitivevalue/css_rem/) | De waarde is een lengte (rem). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_RGBCOLOR](../../aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | De waarde is een RGB-kleur. De waarde kan worden verkregen met behulp van de methode GetRGBColorValue. |
| const [CSS_S](../../aspose.html.dom.css/cssprimitivevalue/css_s/) | De waarde is een tijd(en). De waarde kan worden verkregen met behulp van de methode getFloatValue. |
| const [CSS_STRING](../../aspose.html.dom.css/cssprimitivevalue/css_string/) | De waarde is een STRING. De waarde kan worden verkregen met behulp van de methode getStringValue. |
| const [CSS_UNKNOWN](../../aspose.html.dom.css/cssprimitivevalue/css_unknown/) | De waarde is geen herkende CSS2-waarde. De waarde kan alleen worden verkregen door het cssText-attribuut te gebruiken. |
| const [CSS_URI](../../aspose.html.dom.css/cssprimitivevalue/css_uri/) | De waarde is een URI. De waarde kan worden verkregen met behulp van de methode getStringValue. |
| const [CSS_VH](../../aspose.html.dom.css/cssprimitivevalue/css_vh/) | De waarde is een percentage van de volledige viewporthoogte. |
| const [CSS_VMAX](../../aspose.html.dom.css/cssprimitivevalue/css_vmax/) | De waarde is een percentage van de breedte of hoogte van de viewport, afhankelijk van welke groter is. |
| const [CSS_VMIN](../../aspose.html.dom.css/cssprimitivevalue/css_vmin/) | De waarde is een percentage van de breedte of hoogte van de viewport, afhankelijk van welke kleiner is. |
| const [CSS_VW](../../aspose.html.dom.css/cssprimitivevalue/css_vw/) | De waarde is een percentage van de volledige viewportbreedte. |

### Zie ook

* class [CSSValue](../cssvalue/)
* naamruimte [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* montage [Aspose.HTML](../../)


