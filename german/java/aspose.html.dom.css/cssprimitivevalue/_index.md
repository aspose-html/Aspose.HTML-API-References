---
title: "CSSPrimitiveValue Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.CSSPrimitiveValue Klasse. Die CSSPrimitiveValue Schnittstelle leitet sich von der CSSValue Schnittstelle ab und stellt den aktuell berechneten Wert einer CSS‑Eigenschaft dar."
type: docs

url: /de/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

Das CSSPrimitiveValue‑Interface leitet sich vom CSSValue‑Interface ab und stellt den aktuell berechneten Wert einer CSS‑Eigenschaft dar.

Hinweis: Dieses Interface war Teil eines Versuchs, ein typisiertes CSS‑Object‑Model zu erstellen. Dieser Versuch wurde aufgegeben, und die meisten Browser implementieren es nicht.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Die cssText‑Eigenschaft des [`CSSValue`](../cssvalue/)‑Interfaces repräsentiert den aktuell berechneten CSS‑Eigenschaftswert. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Ein Code, der den Typ des Wertes definiert. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) Der Typ des Wertes, wie durch die oben angegebenen Konstanten definiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Diese Methode wird verwendet, um den Counter‑Wert zu erhalten. Wenn dieser CSS‑Wert keinen Counter‑Wert enthält, wird eine DOMException ausgelöst. Änderungen an der entsprechenden Stil‑Eigenschaft können über die Counter‑Schnittstelle vorgenommen werden. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Diese Methode wird verwendet, um einen Fließkommawert in einer angegebenen Einheit zu erhalten. Wenn dieser CSS-Wert keinen Fließkommawert enthält oder nicht in die angegebene Einheit konvertiert werden kann, wird eine DOMException ausgelöst. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Gibt einen Hashcode für diese Instanz zurück. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Diese Methode wird verwendet, um einen Ganzzahlwert in einer angegebenen Einheit zu erhalten. Wenn dieser CSS-Wert keinen Ganzzahlwert enthält oder nicht in die angegebene Einheit konvertiert werden kann, wird eine DOMException ausgelöst. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Diese Methode wird verwendet, um den Typ eines ECMAScript‑Objekts abzurufen. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Diese Methode wird verwendet, um den Rect-Wert zu erhalten. Wenn dieser CSS-Wert keinen Rect-Wert enthält, wird eine DOMException ausgelöst. Änderungen an der entsprechenden Style-Eigenschaft können über das Rect-Interface vorgenommen werden. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Diese Methode wird verwendet, um die RGB‑Farbe zu erhalten. Wenn dieser CSS-Wert keinen RGB‑Farbwert enthält, wird eine DOMException ausgelöst. Änderungen an der entsprechenden Style-Eigenschaft können über das RGBColor-Interface vorgenommen werden. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | Diese Methode wird verwendet, um den String‑Wert zu erhalten. Wenn der CSS-Wert keinen String‑Wert enthält, wird eine DOMException ausgelöst. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Eine Methode, um den Fließkommawert mit einer angegebenen Einheit zu setzen. Wenn die mit diesem Wert verbundene Eigenschaft die angegebene Einheit oder den Fließkommawert nicht akzeptieren kann, bleibt der Wert unverändert und es wird eine DOMException ausgelöst. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Eine Methode, um den Ganzzahlwert mit einer angegebenen Einheit zu setzen. Wenn die mit diesem Wert verbundene Eigenschaft die angegebene Einheit oder den Ganzzahlwert nicht akzeptieren kann, bleibt der Wert unverändert und es wird eine DOMException ausgelöst. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | Eine Methode, um den String‑Wert mit der angegebenen Einheit zu setzen. Wenn die mit diesem Wert verbundene Eigenschaft die angegebene Einheit oder den String‑Wert nicht akzeptieren kann, bleibt der Wert unverändert und es wird eine DOMException ausgelöst. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | Der Wert ist eine Attributfunktion. Der Wert kann mit der Methode getStringValue abgerufen werden. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | Der Wert ist eine Länge (ch). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | Der Wert ist eine Länge (cm). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | Der Wert ist eine counter‑ oder counters‑Funktion. Der Wert kann mit der Methode GetCounterValue abgerufen werden. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | Der Wert ist ein Winkel (deg). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | Der Wert ist eine Zahl mit unbekannter Dimension. Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | Der Wert ist ein Punkt pro Zentimeter (dpcm). |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | Der Wert ist ein Punkt pro Zoll (dpi). |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | Der Wert ist ein Punkt pro ‘px’-Einheit (dppx). |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | Der Wert ist eine Länge (ems). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | Der Wert ist eine Länge (exs). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | Der Wert ist ein Winkel (grad). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | Der Wert ist eine Frequenz (Hz). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | Der Wert ist ein Bezeichner. Der Wert kann mit der Methode getStringValue abgerufen werden. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | Der Wert ist eine Länge (in). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | Der Wert ist eine Frequenz (kHz). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | Der Wert ist eine Länge (mm). Der Wert kann mit der Methode getFloatValue abgerufen werden. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | Der Wert ist eine Zeit (ms). Der Wert kann durch die Verwendung der Methode getFloatValue erhalten werden. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | Der Wert ist eine einfache Zahl. Der Wert kann durch die Verwendung der Methode getFloatValue erhalten werden. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | Der Wert ist eine Länge (pc). Der Wert kann durch die Verwendung der Methode getFloatValue erhalten werden. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | Der Wert ist ein Prozentsatz. Der Wert kann durch die Verwendung der Methode getFloatValue erhalten werden. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | Der Wert ist eine Länge (pt). Der Wert kann durch die Verwendung der Methode getFloatValue erhalten werden. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | Der Wert ist eine Länge (px). Der Wert kann durch die Verwendung der Methode getFloatValue erhalten werden. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | Der Wert ist ein Winkel (rad). Der Wert kann durch die Verwendung der Methode getFloatValue erhalten werden. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | Der Wert ist eine rect-Funktion. Der Wert kann durch die Verwendung der Methode GetRectValue erhalten werden. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | Der Wert ist eine Länge (rem). Der Wert kann durch die Verwendung der Methode getFloatValue erhalten werden. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | Der Wert ist eine RGB-Farbe. Der Wert kann durch die Verwendung der Methode GetRGBColorValue erhalten werden. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | Der Wert ist eine Zeit (s). Der Wert kann durch die Verwendung der Methode getFloatValue erhalten werden. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | Der Wert ist ein STRING. Der Wert kann durch die Verwendung der Methode getStringValue erhalten werden. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | Der Wert ist kein erkannter CSS2-Wert. Der Wert kann nur durch die Verwendung des Attributs cssText erhalten werden. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | Der Wert ist ein URI. Der Wert kann durch die Verwendung der Methode getStringValue erhalten werden. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | Der Wert ist ein Prozentsatz der vollen Ansichtsfensterhöhe. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | Der Wert ist ein Prozentsatz der Ansichtsfensterbreite oder -höhe, je nachdem, welcher größer ist. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | Der Wert ist ein Prozentsatz der Ansichtsfensterbreite oder -höhe, je nachdem, welcher kleiner ist. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | Der Wert ist ein Prozentsatz der vollen Ansichtsfensterbreite. |

### Siehe auch

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
