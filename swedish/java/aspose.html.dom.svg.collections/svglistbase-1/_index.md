---
title: "SVGListBaseT-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.collections.SVGListBase1T klass. Detta gränssnitt definierar en basklass för alla SVG-listor"
type: docs

url: /sv/java/com.aspose.html.dom.svg.collections/svglistbase-1/
---
## SVGListBase&lt;T&gt; class

Detta gränssnitt definierar en grundlista för alla SVG-listor.

```java
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objekt som lagras i listan. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getItem]
[setItem] Returns the indexth item in the list. |
| [getLength](../../com.aspose.html.dom.svg.collections/svglistbase-1/length/) Antalet objekt i listan. |
| [getNumberOfItems](../../com.aspose.html.dom.svg.collections/svglistbase-1/numberofitems/) Antalet objekt i listan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [appendItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/appenditem/)(T) | Infogar ett nytt objekt i slutet av listan. |
| [clear](../../com.aspose.html.dom.svg.collections/svglistbase-1/clear/)() | Rensar alla befintliga objekt från listan, vilket resulterar i en tom lista. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [getEnumerator](../../com.aspose.html.dom.svg.collections/svglistbase-1/getenumerator/)() | Hämtar enumeratorn. |
| [getItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/getitem/)(ulong) | Returnerar det angivna objektet från listan. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [initialize](../../com.aspose.html.dom.svg.collections/svglistbase-1/initialize/)(T) | Rensar alla befintliga objekt från listan och initierar om listan för att innehålla det enda objektet som anges av parametern. |
| [insertItemBefore](../../com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/)(T, ulong) | Infogar ett nytt objekt i listan på den angivna positionen. Det första objektet har nummer 0. |
| [removeItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/)(ulong) | Tar bort ett befintligt objekt från listan. |
| [replaceItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/)(T, ulong) | Ersätter ett befintligt objekt i listan med ett nytt objekt. |

### Se även

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.collections](../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../)
