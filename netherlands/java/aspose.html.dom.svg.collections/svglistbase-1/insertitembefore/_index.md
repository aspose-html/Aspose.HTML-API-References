---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGListBase-methode. Voegt een nieuw item toe aan de lijst op de opgegeven positie. Het eerste item heeft nummer 0"
type: docs

url: /nl/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Voegt een nieuw item in de lijst in op de opgegeven positie. Het eerste item heeft nummer 0.

```java
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newItem | T | Het item dat in de lijst moet worden ingevoegd. |
| index | UInt64 | De index van het item vóór welk het nieuwe item moet worden ingevoegd. Het eerste item heeft nummer 0. Als de index gelijk is aan 0, wordt het nieuwe item aan het begin van de lijst ingevoegd. Als de index groter dan of gelijk aan numberOfItems is, wordt het nieuwe item aan het einde van de lijst toegevoegd. |

### Retourwaarde

Het ingevoegde item.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Opgetreden wanneer de lijst niet kan worden gewijzigd. |

### Zie ook

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
