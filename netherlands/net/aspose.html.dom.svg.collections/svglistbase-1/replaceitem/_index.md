---
title: SVGListBase1.ReplaceItem
second_title: Aspose.HTML voor .NET API-referentie
description: SVGListBase methode. Vervangt een bestaand item in de lijst door een nieuw item.
type: docs
weight: 110
url: /nl/net/aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Vervangt een bestaand item in de lijst door een nieuw item.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newItem | T | Het item dat in de lijst moet worden ingevoegd. |
| index | UInt64 | De index van het item dat vervangen moet worden. Het eerste item is nummer 0. |

### Winstwaarde

Het ingevoegde item.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Verhoogd wanneer de lijst niet kan worden gewijzigd. |
| [DOMException](../../../aspose.html.dom/domexception/) | Code[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). Wordt verhoogd als het indexnummer groter is dan of gelijk is aan numberOfItems. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* naamruimte [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* montage [Aspose.HTML](../../../)


