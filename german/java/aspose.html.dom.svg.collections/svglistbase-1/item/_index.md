---
title: "SVGListBase-1.Item"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGListBase‑Eigenschaft. Gibt das Element an der Index‑Position in der Liste zurück."
type: docs

url: /de/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Gibt das Element an der Index‑Position in der Liste zurück.

```java
public T this[ulong index] { get; set; }
```

| Parameter | Beschreibung |
| --- | --- |
| index | Index in der Liste. |

### Rückgabewert

Das gespeicherte Objekt an der Index‑Position in der Liste.

### Property Value

Der Typ des in der Liste gespeicherten Elements.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Wird ausgelöst, wenn die Liste nicht geändert werden kann. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Wird ausgelöst, wenn die Indexnummer größer oder gleich numberOfItems ist. |

### Siehe auch

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
