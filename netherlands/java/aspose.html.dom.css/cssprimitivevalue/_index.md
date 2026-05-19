---
title: "CSSPrimitiveValue Class"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.CSSPrimitiveValue class. De CSSPrimitiveValue‑interface is afgeleid van de CSSValue‑interface en vertegenwoordigt de momenteel berekende waarde van een CSS‑eigenschap."
type: docs

url: /nl/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

De CSSPrimitiveValue-interface is afgeleid van de CSSValue-interface en vertegenwoordigt de huidige berekende waarde van een CSS‑eigenschap.

Opmerking: Deze interface maakte deel uit van een poging om een getypeerd CSS Object Model te creëren. Deze poging is opgegeven, en de meeste browsers implementeren het niet.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | De cssText‑eigenschap van de [`CSSValue`](../cssvalue/) interface vertegenwoordigt de huidige berekende CSS‑eigenschapswaarde. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Een code die het type van de waarde definieert. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) Het type van de waarde zoals gedefinieerd door de hierboven gespecificeerde constanten. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Deze methode wordt gebruikt om de Counter‑waarde op te halen. Als deze CSS‑waarde geen counter‑waarde bevat, wordt een DOMException opgegooid. Aanpassing van de overeenkomstige stijl‑eigenschap kan worden bereikt met behulp van de Counter‑interface. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Deze methode wordt gebruikt om een float‑waarde op te halen in een opgegeven eenheid. Als deze CSS‑waarde geen float‑waarde bevat of niet kan worden omgezet naar de opgegeven eenheid, wordt een DOMException opgegooid. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Retourneert een hashcode voor deze instantie. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Deze methode wordt gebruikt om een int‑waarde op te halen in een opgegeven eenheid. Als deze CSS‑waarde geen int‑waarde bevat of niet kan worden omgezet naar de opgegeven eenheid, wordt een DOMException opgegooid. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Deze methode wordt gebruikt om de Rect‑waarde op te halen. Als deze CSS‑waarde geen rect‑waarde bevat, wordt een DOMException opgegooid. Aanpassing van de overeenkomstige stijl‑eigenschap kan worden bereikt met behulp van de Rect‑interface. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Deze methode wordt gebruikt om de RGB‑kleur op te halen. Als deze CSS‑waarde geen RGB‑kleurwaarde bevat, wordt een DOMException opgegooid. Aanpassing van de overeenkomstige stijl‑eigenschap kan worden bereikt met behulp van de RGBColor‑interface. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | Deze methode wordt gebruikt om de String‑waarde op te halen. Als de CSS‑waarde geen String‑waarde bevat, wordt een DOMException opgegooid. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Een methode om de float‑waarde in te stellen met een opgegeven eenheid. Als de eigenschap die aan deze waarde is gekoppeld de opgegeven eenheid of de float‑waarde niet accepteert, blijft de waarde ongewijzigd en wordt een DOMException opgegooid. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Een methode om de int‑waarde in te stellen met een opgegeven eenheid. Als de eigenschap die aan deze waarde is gekoppeld de opgegeven eenheid of de int‑waarde niet accepteert, blijft de waarde ongewijzigd en wordt een DOMException opgegooid. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | Een methode om de String‑waarde in te stellen met de opgegeven eenheid. Als de eigenschap die aan deze waarde is gekoppeld de opgegeven eenheid of de String‑waarde niet accepteert, blijft de waarde ongewijzigd en wordt een DOMException opgegooid. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | De waarde is een attribuut‑functie. De waarde kan worden verkregen met de methode getStringValue. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | De waarde is een lengte (ch). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | De waarde is een lengte (cm). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | De waarde is een teller‑ of tellers‑functie. De waarde kan worden verkregen met de methode GetCounterValue. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | De waarde is een hoek (deg). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | De waarde is een getal met een onbekende dimensie. De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | De waarde is een dots per centimeter (dpcm). |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | De waarde is een dots per inch (dpi). |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | De waarde is een dots per ‘px’-eenheid (dppx). |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | De waarde is een lengte (ems). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | De waarde is een lengte (exs). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | De waarde is een hoek (grad). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | De waarde is een frequentie (Hz). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | De waarde is een identifier. De waarde kan worden verkregen met de methode getStringValue. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | De waarde is een lengte (in). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | De waarde is een frequentie (kHz). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | De waarde is een lengte (mm). De waarde kan worden verkregen met de methode getFloatValue. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | De waarde is een tijd (ms). De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | De waarde is een eenvoudig getal. De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | De waarde is een lengte (pc). De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | De waarde is een percentage. De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | De waarde is een lengte (pt). De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | De waarde is een lengte (px). De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | De waarde is een hoek (rad). De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | De waarde is een rect-functie. De waarde kan worden verkregen door de GetRectValue-methode te gebruiken. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | De waarde is een lengte (rem). De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | De waarde is een RGB-kleur. De waarde kan worden verkregen door de GetRGBColorValue-methode te gebruiken. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | De waarde is een tijd (s). De waarde kan worden verkregen door de getFloatValue-methode te gebruiken. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | De waarde is een STRING. De waarde kan worden verkregen door de getStringValue-methode te gebruiken. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | De waarde is geen herkende CSS2-waarde. De waarde kan alleen worden verkregen door het cssText-attribuut te gebruiken. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | De waarde is een URI. De waarde kan worden verkregen door de getStringValue-methode te gebruiken. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | De waarde is een percentage van de volledige viewporthoogte. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | De waarde is een percentage van de viewportbreedte of -hoogte, afhankelijk van welke groter is. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | De waarde is een percentage van de viewportbreedte of -hoogte, afhankelijk van welke kleiner is. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | De waarde is een percentage van de volledige viewportbreedte. |

### Zie ook

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
