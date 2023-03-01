---
title: SVGListBase1.Item
second_title: Aspose.HTML voor .NET API-referentie
description: SVGListBase eigendom. Retourneert het geïndexeerde item in de lijst.
type: docs
weight: 10
url: /nl/net/aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Retourneert het geïndexeerde item in de lijst.

```csharp
public T this[ulong index] { get; set; }
```

| Parameter | Beschrijving |
| --- | --- |
| index | Indexeren in de lijst. |

### Winstwaarde

Het opgeslagen object op de indexste positie in de lijst.

### Eigendoms-waarde

Het type item dat is opgeslagen in de lijst.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Verhoogd wanneer de lijst niet kan worden gewijzigd. |
| [DOMException](../../../aspose.html.dom/domexception/) | Code[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). Wordt verhoogd als het indexnummer groter is dan of gelijk is aan numberOfItems. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* naamruimte [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* montage [Aspose.HTML](../../../)


