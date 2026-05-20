---
title: "SVGListBase-1.GetItem"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGListBase-metod. Returnerar det specificerade objektet från listan"
type: docs

url: /sv/java/com.aspose.html.dom.svg.collections/svglistbase-1/getitem/
---
## SVGListBase&lt;T&gt;.GetItem method

Returnerar det angivna objektet från listan.

```java
public T GetItem(ulong index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | UInt64 | Indexet för objektet från listan som ska returneras. Det första objektet har nummer 0. |

### Returvärde

Det valda objektet.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Uppstår om indexnumret är större än eller lika med numberOfItems. |

### Se även

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
