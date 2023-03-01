---
title: SVGListBase1.ReplaceItem
second_title: Aspose.HTML für .NET-API-Referenz
description: SVGListBase methode. Ersetzt ein vorhandenes Element in der Liste durch ein neues Element.
type: docs
weight: 110
url: /de/net/aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Ersetzt ein vorhandenes Element in der Liste durch ein neues Element.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newItem | T | Das Element, das in die Liste eingefügt werden soll. |
| index | UInt64 | Der Index des zu ersetzenden Elements. Das erste Element ist die Nummer 0. |

### Rückgabewert

Das eingefügte Element.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Wird ausgelöst, wenn die Liste nicht geändert werden kann. |
| [DOMException](../../../aspose.html.dom/domexception/) | Code[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). Wird ausgelöst, wenn die Indexnummer größer oder gleich numberOfItems ist. |

### Siehe auch

* class [SVGListBase&lt;T&gt;](../)
* namensraum [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* Montage [Aspose.HTML](../../../)


