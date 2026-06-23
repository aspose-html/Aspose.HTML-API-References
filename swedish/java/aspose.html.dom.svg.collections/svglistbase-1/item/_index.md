---
title: "SVGListBase-1.Item"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGListBase‑egenskap. Returnerar det indexte elementet i listan"
type: docs

url: /sv/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Returnerar det indexte elementet i listan.

```java
public T this[ulong index] { get; set; }
```

| Parameter | Beskrivning |
| --- | --- |
| index | Index i listan. |

### Returvärde

Det lagrade objektet på den indexte positionen i listan.

### Property Value

Typen av objekt som lagras i listan.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Uppstår när listan inte kan modifieras. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Uppstår om indexnumret är större än eller lika med numberOfItems. |

### Se även

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
