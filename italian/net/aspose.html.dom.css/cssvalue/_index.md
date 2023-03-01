---
title: Class CSSValue
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Css.CSSValue classe. Rappresenta un valore semplice o complesso. Un oggetto CSSValue si verifica solo in un contesto di una proprietà CSS.
type: docs
weight: 340
url: /it/net/aspose.html.dom.css/cssvalue/
---
## CSSValue class

Rappresenta un valore semplice o complesso. Un oggetto CSSValue si verifica solo in un contesto di una proprietà CSS.

```csharp
public abstract class CSSValue : DOMObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Una rappresentazione in forma di stringa del valore corrente. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | Un codice che definisce il tipo di valore. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Determina se specificatoObject è uguale a questa istanza. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Restituisce un codice hash per questa istanza. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | Restituisce aString che rappresenta questa istanza. |
| [operator ==](../../aspose.html.dom.css/cssvalue/op_equality/) | Implementa l'operatore ==. |
| [operator !=](../../aspose.html.dom.css/cssvalue/op_inequality/) | Implementa l'operatore !=. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.html.dom.css/cssvalue/css_custom/) | Il valore è un valore personalizzato. |
| const [CSS_INHERIT](../../aspose.html.dom.css/cssvalue/css_inherit/) | Il valore viene ereditato e il cssText contiene "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.html.dom.css/cssvalue/css_primitive_value/) | Il valore è un valore primitivo ed è possibile ottenere un'istanza dell'interfaccia CSSPrimitiveValue utilizzando metodi di cast specifici dell'associazione su questa istanza dell'interfaccia CSSValue. |
| const [CSS_VALUE_LIST](../../aspose.html.dom.css/cssvalue/css_value_list/) | Il valore è un elenco CSSValue e un'istanza dell'interfaccia CSSValueList può essere ottenuta utilizzando metodi di casting specifici dell'associazione su questa istanza dell'interfaccia CSSValue. |

### Guarda anche

* class [DOMObject](../../aspose.html.dom/domobject/)
* spazio dei nomi [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assemblea [Aspose.HTML](../../)


