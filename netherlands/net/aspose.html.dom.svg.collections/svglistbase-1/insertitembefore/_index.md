---
title: SVGListBase1.InsertItemBefore
second_title: Aspose.HTML voor .NET API-referentie
description: SVGListBase methode. Voegt een nieuw item in de lijst in op de gespecificeerde positie. Het eerste item is nummer 0.
type: docs
weight: 90
url: /nl/net/aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Voegt een nieuw item in de lijst in op de gespecificeerde positie. Het eerste item is nummer 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newItem | T | Het item dat in de lijst moet worden ingevoegd. |
| index | UInt64 | De index van het item waarvoor het nieuwe item moet worden ingevoegd. Het eerste item is nummer 0. Als de index gelijk is aan 0, wordt het nieuwe item vooraan in de lijst ingevoegd. Als de index groter is dan of gelijk is aan numberOfItems, wordt het nieuwe item toegevoegd aan het einde van de lijst. |

### Winstwaarde

Het ingevoegde item.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Verhoogd wanneer de lijst niet kan worden gewijzigd. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* naamruimte [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* montage [Aspose.HTML](../../../)


