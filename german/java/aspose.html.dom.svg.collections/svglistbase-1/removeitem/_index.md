---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGListBase‑Methode. Entfernt ein vorhandenes Element aus der Liste."
type: docs

url: /de/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Entfernt ein vorhandenes Element aus der Liste.

```java
public T RemoveItem(ulong index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | UInt64 | Der Index des zu entfernenden Elements. Das erste Element hat die Nummer 0. |

### Rückgabewert

Das entfernte Element.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Wird ausgelöst, wenn die Liste nicht geändert werden kann. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Wird ausgelöst, wenn die Indexnummer größer oder gleich numberOfItems ist. |

### Siehe auch

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
