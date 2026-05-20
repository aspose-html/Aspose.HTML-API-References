---
title: "CSSValue‑klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.CSSValue‑klass. Representerar ett enkelt eller komplext värde. Ett CSSValue‑objekt förekommer endast i ett sammanhang med en CSS‑egenskap."
type: docs

url: /sv/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

Representerar ett enkelt eller ett komplext värde. Ett CSSValue‑objekt förekommer endast i samband med en CSS‑egenskap.

```java
public abstract class CSSValue : DOMObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | cssText‑egenskapen i `CSSValue`‑gränssnittet representerar det aktuella beräknade CSS‑egenskapsvärdet. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) En kod som definierar värdets typ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Avgör om det angivna objektet är lika med denna instans. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Returnerar en hashkod för detta objekt. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Denna metod används för att hämta ECMAScript‑objekttypen. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Returnerar en sträng som representerar detta objekt. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | Värdet är ett anpassat värde. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | Värdet är ärvt och cssText innehåller "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | Värdet är ett primitivt värde och en instans av CSSPrimitiveValue‑gränssnittet kan erhållas genom att använda bindningsspecifika kastmetoder på denna instans av CSSValue‑gränssnittet. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | Värdet är en CSSValue-lista och en instans av CSSValueList-gränssnittet kan erhållas genom att använda bindningsspecifika kastmetoder på denna instans av CSSValue-gränssnittet. |

### Se även

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
