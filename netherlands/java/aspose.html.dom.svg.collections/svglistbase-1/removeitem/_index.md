---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGListBase-methode. Verwijdert een bestaand item uit de lijst"
type: docs

url: /nl/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Verwijdert een bestaand item uit de lijst.

```java
public T RemoveItem(ulong index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | UInt64 | De index van het item dat verwijderd moet worden. Het eerste item heeft nummer 0. |

### Retourwaarde

Het verwijderde item.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Opgetreden wanneer de lijst niet kan worden gewijzigd. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Opgetreden als het indexnummer groter dan of gelijk aan numberOfItems is. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
