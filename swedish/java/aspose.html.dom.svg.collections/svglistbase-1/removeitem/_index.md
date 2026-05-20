---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGListBase-metod. Tar bort ett befintligt objekt från listan"
type: docs

url: /sv/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Tar bort ett befintligt objekt från listan.

```java
public T RemoveItem(ulong index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | UInt64 | Indexet för objektet som ska tas bort. Det första objektet har nummer 0. |

### Returvärde

Det borttagna objektet.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Uppstår när listan inte kan modifieras. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Uppstår om indexnumret är större än eller lika med numberOfItems. |

### Se även

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
