---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGListBase‑metod. Ersätter ett befintligt objekt i listan med ett nytt objekt."
type: docs

url: /sv/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Ersätter ett befintligt objekt i listan med ett nytt objekt.

```java
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newItem | T | Objektet som ska infogas i listan. |
| index | UInt64 | Indexet för det objekt som ska ersättas. Det första objektet är nummer 0. |

### Returvärde

Det infogade objektet.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Uppstår när listan inte kan modifieras. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Uppstår om indexnumret är större än eller lika med numberOfItems. |

### Se även

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
