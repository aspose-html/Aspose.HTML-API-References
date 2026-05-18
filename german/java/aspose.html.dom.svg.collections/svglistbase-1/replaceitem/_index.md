---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGListBase-Methode. Ersetzt ein vorhandenes Element in der Liste durch ein neues Element"
type: docs

url: /de/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Ersetzt ein vorhandenes Element in der Liste durch ein neues Element.

```java
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newItem | T | Das Element, das in die Liste eingefügt werden soll. |
| index | UInt64 | Der Index des Elements, das ersetzt werden soll. Das erste Element hat die Nummer 0. |

### Rückgabewert

Das eingefügte Element.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Wird ausgelöst, wenn die Liste nicht geändert werden kann. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Wird ausgelöst, wenn die Indexnummer größer oder gleich numberOfItems ist. |

### Siehe auch

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
