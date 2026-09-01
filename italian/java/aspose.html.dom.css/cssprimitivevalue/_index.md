---
title: "Classe CSSPrimitiveValue"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.dom.css.CSSPrimitiveValue classe. L'interfaccia CSSPrimitiveValue deriva dall'interfaccia CSSValue e rappresenta il valore calcolato corrente di una proprietà CSS."
type: docs

url: /it/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

L'interfaccia CSSPrimitiveValue deriva dall'interfaccia CSSValue e rappresenta il valore calcolato corrente di una proprietà CSS.

Nota: Questa interfaccia faceva parte di un tentativo di creare un modello di oggetti CSS tipizzato. Questo tentativo è stato abbandonato e la maggior parte dei browser non lo implementa.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | La proprietà cssText dell'interfaccia [`CSSValue`](../cssvalue/) rappresenta il valore corrente della proprietà CSS calcolata. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Un codice che definisce il tipo del valore. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) Il tipo del valore come definito dalle costanti specificate sopra. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Determina se l'Object specificato è uguale a questa istanza. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Questo metodo è usato per ottenere il valore Counter. Se questo valore CSS non contiene un valore counter, viene sollevata una DOMException. La modifica della proprietà di stile corrispondente può essere effettuata usando l'interfaccia Counter. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Questo metodo è usato per ottenere un valore float in un'unità specificata. Se questo valore CSS non contiene un valore float o non può essere convertito nell'unità specificata, viene sollevata una DOMException. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Restituisce un codice hash per questa istanza. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Questo metodo è usato per ottenere un valore int in un'unità specificata. Se questo valore CSS non contiene un valore int o non può essere convertito nell'unità specificata, viene sollevata una DOMException. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Questo metodo è usato per recuperare il tipo di oggetto ECMAScript. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Questo metodo è usato per ottenere il valore Rect. Se questo valore CSS non contiene un valore rect, viene sollevata una DOMException. La modifica della proprietà di stile corrispondente può essere effettuata usando l'interfaccia Rect. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Questo metodo è usato per ottenere il colore RGB. Se questo valore CSS non contiene un valore colore RGB, viene sollevata una DOMException. La modifica della proprietà di stile corrispondente può essere effettuata usando l'interfaccia RGBColor. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | Questo metodo è usato per ottenere il valore String. Se il valore CSS non contiene un valore String, viene sollevata una DOMException. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Un metodo per impostare il valore float con un'unità specificata. Se la proprietà associata a questo valore non può accettare l'unità specificata o il valore float, il valore rimarrà invariato e verrà sollevata una DOMException. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Un metodo per impostare il valore int con un'unità specificata. Se la proprietà associata a questo valore non può accettare l'unità specificata o il valore int, il valore rimarrà invariato e verrà sollevata una DOMException. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | Un metodo per impostare il valore String con l'unità specificata. Se la proprietà associata a questo valore non può accettare l'unità specificata o il valore String, il valore rimarrà invariato e verrà sollevata una DOMException. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Restituisce una stringa che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | Il valore è una funzione attributo. Il valore può essere ottenuto usando il metodo getStringValue. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | Il valore è una lunghezza (ch). Il valore può essere ottenuto usando il metodo getFloatValue. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | Il valore è una lunghezza (cm). Il valore può essere ottenuto usando il metodo getFloatValue. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | Il valore è una funzione counter o counters. Il valore può essere ottenuto usando il metodo GetCounterValue. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | Il valore è un angolo (deg). Il valore può essere ottenuto usando il metodo getFloatValue. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | Il valore è un numero con una dimensione sconosciuta. Il valore può essere ottenuto usando il metodo getFloatValue. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | Il valore è punti per centimetro (dpcm). |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | Il valore è punti per pollice (dpi). |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | Il valore è punti per unità ‘px’ (dppx). |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | Il valore è una lunghezza (ems). Il valore può essere ottenuto usando il metodo getFloatValue. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | Il valore è una lunghezza (exs). Il valore può essere ottenuto usando il metodo getFloatValue. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | Il valore è un angolo (grad). Il valore può essere ottenuto usando il metodo getFloatValue. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | Il valore è una frequenza (Hz). Il valore può essere ottenuto usando il metodo getFloatValue. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | Il valore è un identificatore. Il valore può essere ottenuto usando il metodo getStringValue. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | Il valore è una lunghezza (in). Il valore può essere ottenuto usando il metodo getFloatValue. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | Il valore è una frequenza (kHz). Il valore può essere ottenuto usando il metodo getFloatValue. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | Il valore è una lunghezza (mm). Il valore può essere ottenuto usando il metodo getFloatValue. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | Il valore è un tempo (ms). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | Il valore è un numero semplice. Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | Il valore è una lunghezza (pc). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | Il valore è una percentuale. Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | Il valore è una lunghezza (pt). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | Il valore è una lunghezza (px). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | Il valore è un angolo (rad). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | Il valore è una funzione rect. Il valore può essere ottenuto utilizzando il metodo GetRectValue. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | Il valore è una lunghezza (rem). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | Il valore è un colore RGB. Il valore può essere ottenuto utilizzando il metodo GetRGBColorValue. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | Il valore è un tempo (s). Il valore può essere ottenuto utilizzando il metodo getFloatValue. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | Il valore è una STRINGA. Il valore può essere ottenuto utilizzando il metodo getStringValue. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | Il valore non è un valore CSS2 riconosciuto. Il valore può essere ottenuto solo utilizzando l'attributo cssText. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | Il valore è un URI. Il valore può essere ottenuto utilizzando il metodo getStringValue. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | Il valore è una percentuale dell'altezza totale della viewport. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | Il valore è una percentuale della larghezza o dell'altezza della viewport, a seconda di quale sia maggiore. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | Il valore è una percentuale della larghezza o dell'altezza della viewport, a seconda di quale sia minore. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | Il valore è una percentuale della larghezza totale della viewport. |

### Vedi anche

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
