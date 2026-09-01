---
title: "SVGListBase-1.Item"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGListBase-eigenschap. Retourneert het item op de indexpositie in de lijst"
type: docs

url: /nl/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Retourneert het item op de indexpositie in de lijst.

```java
public T this[ulong index] { get; set; }
```

| Parameter | Beschrijving |
| --- | --- |
| index | Index in de lijst. |

### Retourwaarde

Het opgeslagen object op de indexpositie in de lijst.

### Property Value

Het type van het opgeslagen item in de lijst.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Opgetreden wanneer de lijst niet kan worden gewijzigd. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Opgetreden als het indexnummer groter dan of gelijk aan numberOfItems is. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
