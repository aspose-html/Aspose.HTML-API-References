---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGListBase-metod. Infogar ett nytt objekt i listan på den angivna positionen. Det första objektet är nummer 0"
type: docs

url: /sv/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Infogar ett nytt objekt i listan på den angivna positionen. Det första objektet har nummer 0.

```java
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newItem | T | Objektet som ska infogas i listan. |
| index | UInt64 | Indexet för det objekt före vilket det nya objektet ska infogas. Det första objektet är nummer 0. Om indexet är lika med 0 infogas det nya objektet i början av listan. Om indexet är större än eller lika med numberOfItems läggs det nya objektet till i slutet av listan. |

### Returvärde

Det infogade objektet.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Uppstår när listan inte kan modifieras. |

### Se även

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
