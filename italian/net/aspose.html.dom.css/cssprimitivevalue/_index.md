---
title: Class CSSPrimitiveValue
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Css.CSSPrimitiveValue classe. Linterfaccia CSSPrimitiveValue rappresenta un singolo valore CSS. Questa interfaccia può essere utilizzata per determinare il valore di una proprietà di stile specifica attualmente impostata in un blocco o per impostare una proprietà di stile specifica in modo esplicito allinterno del blocco. Unistanza di questa interfaccia potrebbe essere ottenuta dal metodo getPropertyCSSValue dellinterfaccia CSSStyleDeclaration. Un oggetto CSSPrimitiveValue si verifica solo in un contesto di una proprietà CSS.
type: docs
weight: 330
url: /it/net/aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

L'interfaccia CSSPrimitiveValue rappresenta un singolo valore CSS. Questa interfaccia può essere utilizzata per determinare il valore di una proprietà di stile specifica attualmente impostata in un blocco o per impostare una proprietà di stile specifica in modo esplicito all'interno del blocco. Un'istanza di questa interfaccia potrebbe essere ottenuta dal metodo getPropertyCSSValue dell'interfaccia CSSStyleDeclaration. Un oggetto CSSPrimitiveValue si verifica solo in un contesto di una proprietà CSS.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Una rappresentazione in forma di stringa del valore corrente. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | Un codice che definisce il tipo di valore. |
| [PrimitiveType](../../aspose.html.dom.css/cssprimitivevalue/primitivetype/) { get; } | Il tipo di valore definito dalle costanti sopra specificate. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Determina se specificatoObject è uguale a questa istanza. |
| abstract [GetCounterValue](../../aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Questo metodo viene utilizzato per ottenere il valore del contatore. Se questo valore CSS non contiene un valore contatore, viene sollevata un'eccezione DOMException. La modifica della proprietà di stile corrispondente può essere ottenuta utilizzando l'interfaccia Counter. |
| abstract [GetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Questo metodo viene utilizzato per ottenere un valore float in un'unità specificata. Se questo valore CSS non contiene un valore float o non può essere convertito nell'unità specificata, viene sollevata un'eccezione DOMException. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Restituisce un codice hash per questa istanza. |
| abstract [GetIntValue](../../aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Questo metodo viene utilizzato per ottenere un valore int in un'unità specificata. Se questo valore CSS non contiene un valore int o non può essere convertito nell'unità specificata, viene sollevata un'eccezione DOMException. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| abstract [GetRectValue](../../aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Questo metodo viene utilizzato per ottenere il valore Rect. Se questo valore CSS non contiene un valore rect, viene sollevata un'eccezione DOMException. La modifica della proprietà di stile corrispondente può essere ottenuta utilizzando l'interfaccia Rect. |
| abstract [GetRGBColorValue](../../aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Questo metodo viene utilizzato per ottenere il colore RGB. Se questo valore CSS non contiene un valore di colore RGB, viene sollevata un'eccezione DOMException. La modifica della proprietà di stile corrispondente può essere ottenuta utilizzando l'interfaccia RGBColor. |
| abstract [GetStringValue](../../aspose.html.dom.css/cssprimitivevalue/getstringvalue/)() | Questo metodo viene utilizzato per ottenere il valore della stringa. Se il valore CSS non contiene un valore stringa, viene sollevata un'eccezione DOMException. |
| abstract [SetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Un metodo per impostare il valore float con un'unità specificata. Se la proprietà associata a questo valore non può accettare l'unità specificata o il valore float, il valore rimarrà invariato e verrà sollevata una DOMException. |
| abstract [SetIntValue](../../aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Un metodo per impostare il valore int con un'unità specificata. Se la proprietà associata a questo valore non può accettare l'unità specificata o il valore int, il valore rimarrà invariato e verrà sollevata un'eccezione DOMException. |
| abstract [SetStringValue](../../aspose.html.dom.css/cssprimitivevalue/setstringvalue/)(ushort, string) | Un metodo per impostare il valore della stringa con l'unità specificata. Se la proprietà associata a questo valore non può accettare l'unità specificata o il valore stringa, il valore rimarrà invariato e verrà sollevata un'eccezione DOMException. |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [CSS_ATTR](../../aspose.html.dom.css/cssprimitivevalue/css_attr/) | Il valore è una funzione di attributo. Il valore può essere ottenuto utilizzando il metodo getStringValue. |
| const [CSS_CH](../../aspose.html.dom.css/cssprimitivevalue/css_ch/) | Il valore è una lunghezza (ch). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_CM](../../aspose.html.dom.css/cssprimitivevalue/css_cm/) | Il valore è una lunghezza (cm). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_COUNTER](../../aspose.html.dom.css/cssprimitivevalue/css_counter/) | Il valore è una funzione contatore o contatori. Il valore può essere ottenuto utilizzando il metodo GetCounterValue. |
| const [CSS_DEG](../../aspose.html.dom.css/cssprimitivevalue/css_deg/) | Il valore è un angolo (deg). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_DIMENSION](../../aspose.html.dom.css/cssprimitivevalue/css_dimension/) | Il valore è un numero con una dimensione sconosciuta. Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_DPCM](../../aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | Il valore è in punti per centimetro (dpcm). |
| const [CSS_DPI](../../aspose.html.dom.css/cssprimitivevalue/css_dpi/) | Il valore è in punti per pollice (dpi). |
| const [CSS_DPPX](../../aspose.html.dom.css/cssprimitivevalue/css_dppx/) | Il valore è un punto per unità 'px' (dppx). |
| const [CSS_EMS](../../aspose.html.dom.css/cssprimitivevalue/css_ems/) | Il valore è una lunghezza (ems). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_EXS](../../aspose.html.dom.css/cssprimitivevalue/css_exs/) | Il valore è una lunghezza (exs). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_GRAD](../../aspose.html.dom.css/cssprimitivevalue/css_grad/) | Il valore è un angolo (grad). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_HZ](../../aspose.html.dom.css/cssprimitivevalue/css_hz/) | Il valore è una frequenza (Hz). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_IDENT](../../aspose.html.dom.css/cssprimitivevalue/css_ident/) | Il valore è un identificatore. Il valore può essere ottenuto utilizzando il metodo getStringValue. |
| const [CSS_IN](../../aspose.html.dom.css/cssprimitivevalue/css_in/) | Il valore è una lunghezza (in). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_KHZ](../../aspose.html.dom.css/cssprimitivevalue/css_khz/) | Il valore è una frequenza (kHz). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_MM](../../aspose.html.dom.css/cssprimitivevalue/css_mm/) | Il valore è una lunghezza (mm). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_MS](../../aspose.html.dom.css/cssprimitivevalue/css_ms/) | Il valore è un tempo (ms). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_NUMBER](../../aspose.html.dom.css/cssprimitivevalue/css_number/) | Il valore è un numero semplice. Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_PC](../../aspose.html.dom.css/cssprimitivevalue/css_pc/) | Il valore è una lunghezza (pc). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.html.dom.css/cssprimitivevalue/css_percentage/) | Il valore è una percentuale. Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_PT](../../aspose.html.dom.css/cssprimitivevalue/css_pt/) | Il valore è una lunghezza (pt). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_PX](../../aspose.html.dom.css/cssprimitivevalue/css_px/) | Il valore è una lunghezza (px). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_RAD](../../aspose.html.dom.css/cssprimitivevalue/css_rad/) | Il valore è un angolo (rad). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_RECT](../../aspose.html.dom.css/cssprimitivevalue/css_rect/) | Il valore è una funzione rect. Il valore può essere ottenuto utilizzando il metodo GetRectValue. |
| const [CSS_REM](../../aspose.html.dom.css/cssprimitivevalue/css_rem/) | Il valore è una lunghezza (rem). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_RGBCOLOR](../../aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | Il valore è un colore RGB. Il valore può essere ottenuto utilizzando il metodo GetRGBColorValue. |
| const [CSS_S](../../aspose.html.dom.css/cssprimitivevalue/css_s/) | Il valore è un tempo (s). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_STRING](../../aspose.html.dom.css/cssprimitivevalue/css_string/) | Il valore è una STRINGA. Il valore può essere ottenuto utilizzando il metodo getStringValue. |
| const [CSS_UNKNOWN](../../aspose.html.dom.css/cssprimitivevalue/css_unknown/) | Il valore non è un valore CSS2 riconosciuto. Il valore può essere ottenuto solo utilizzando l'attributo cssText. |
| const [CSS_URI](../../aspose.html.dom.css/cssprimitivevalue/css_uri/) | Il valore è un URI. Il valore può essere ottenuto utilizzando il metodo getStringValue. |
| const [CSS_VH](../../aspose.html.dom.css/cssprimitivevalue/css_vh/) | Il valore è una percentuale dell'altezza completa della finestra. |
| const [CSS_VMAX](../../aspose.html.dom.css/cssprimitivevalue/css_vmax/) | Il valore è una percentuale della larghezza o dell'altezza del viewport, qualunque sia maggiore. |
| const [CSS_VMIN](../../aspose.html.dom.css/cssprimitivevalue/css_vmin/) | Il valore è una percentuale della larghezza o dell'altezza della finestra, a seconda di quale sia inferiore. |
| const [CSS_VW](../../aspose.html.dom.css/cssprimitivevalue/css_vw/) | Il valore è una percentuale della larghezza completa della finestra. |

### Guarda anche

* class [CSSValue](../cssvalue/)
* spazio dei nomi [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assemblea [Aspose.HTML](../../)


