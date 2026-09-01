---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGListBase methode. Vervangt een bestaand item in de lijst door een nieuw item"
type: docs

url: /nl/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Vervangt een bestaand item in de lijst door een nieuw item.

```java
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newItem | T | Het item dat in de lijst moet worden ingevoegd. |
| index | UInt64 | De index van het item dat moet worden vervangen. Het eerste item heeft nummer 0. |

### Retourwaarde

Het ingevoegde item.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Opgetreden wanneer de lijst niet kan worden gewijzigd. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Opgetreden als het indexnummer groter dan of gelijk aan numberOfItems is. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
