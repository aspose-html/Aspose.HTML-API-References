---
title: "CSSValueList‑klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.CSSValueList‑klass. CSSValueList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS‑värden."
type: docs

url: /sv/java/com.aspose.html.dom.css/cssvaluelist/
---
## CSSValueList class

CSSValueList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS‑värden.

Obs: Detta gränssnitt var en del av ett försök att skapa en typad CSS‑objektmodell. Försöket har övergetts, och de flesta webbläsare implementerar det inte.

```java
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | Initierar en ny instans av `CSSValueList`‑klassen. |
| [CSSValueList](cssvaluelist/#constructor_1)(params CSSValue[]) | Initierar en ny instans av `CSSValueList`‑klassen. |
| [CSSValueList](cssvaluelist/#constructor_2)(IEnumerable&lt;CSSValue&gt;) | Initierar en ny instans av `CSSValueList`‑klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [cSSText](../../com.aspose.html.dom.css/cssvaluelist/csstext/) { get; set; } | cssText‑egenskapen för [`CSSValue`](../cssvalue/)‑gränssnittet representerar det aktuella beräknade CSS‑egenskapsvärdet. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) En kod som definierar värdets typ. |
| [getItem](../../com.aspose.html.dom.css/cssvaluelist/item/) item()‑metoden för CSSValueList‑gränssnittet används för att hämta ett CSSValue efter ordinalt index. |
| [getLength](../../com.aspose.html.dom.css/cssvaluelist/length/) length‑egenskapen (skrivskyddad) för CSSValueList‑gränssnittet representerar antalet CSSValue‑objekt i listan. Giltigt intervall för index är 0 till length‑1 inklusive. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Avgör om det angivna objektet är lika med denna instans. |
| [getEnumerator](../../com.aspose.html.dom.css/cssvaluelist/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Returnerar en hashkod för detta objekt. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvaluelist/getplatformtype/)() | Denna metod används för att hämta ECMAScript‑objekttypen. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Returnerar en sträng som representerar detta objekt. |

### Se även

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
