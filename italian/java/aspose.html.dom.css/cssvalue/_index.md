---
title: "Classe CSSValue"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.dom.css.CSSValue. Rappresenta un valore semplice o complesso. Un oggetto CSSValue si verifica solo in un contesto di una proprietà CSS."
type: docs

url: /it/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

Rappresenta un valore semplice o complesso. Un oggetto CSSValue si verifica solo in un contesto di una proprietà CSS.

```java
public abstract class CSSValue : DOMObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | La proprietà cssText dell'interfaccia `CSSValue` rappresenta il valore corrente della proprietà CSS calcolata. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Un codice che definisce il tipo del valore. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Determina se l'Object specificato è uguale a questa istanza. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Restituisce un codice hash per questa istanza. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Questo metodo è usato per recuperare il Tipo di oggetto ECMAScript. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Restituisce una String che rappresenta questa istanza. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | Il valore è un valore personalizzato. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | Il valore è ereditato e il cssText contiene \"inherit\". |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | Il valore è un valore primitivo e un'istanza dell'interfaccia CSSPrimitiveValue può essere ottenuta usando metodi di casting specifici del binding su questa istanza dell'interfaccia CSSValue. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | Il valore è un elenco di CSSValue e un'istanza dell'interfaccia CSSValueList può essere ottenuta utilizzando metodi di casting specifici del binding su questa istanza dell'interfaccia CSSValue. |

### Vedi anche

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
