---
title: "SVGListBase-1.GetItem"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGListBase-methode. Retourneert het opgegeven item uit de lijst"
type: docs

url: /nl/java/com.aspose.html.dom.svg.collections/svglistbase-1/getitem/
---
## SVGListBase&lt;T&gt;.GetItem method

Retourneert het opgegeven item uit de lijst.

```java
public T GetItem(ulong index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | UInt64 | De index van het item uit de lijst dat moet worden geretourneerd. Het eerste item heeft nummer 0. |

### Retourwaarde

Het geselecteerde item.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Opgetreden als het indexnummer groter dan of gelijk aan numberOfItems is. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
