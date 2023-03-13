---
title: Interface IElementTraversal
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Traversal.IElementTraversal koppel. De ElementTraversalinterface is een set alleenlezen attributen waarmee een auteur gemakkelijk tussen elementen in een document kan navigeren. Bij conforme implementaties van Element Traversal moeten alle objecten die Element implementeren ook de ElementTraversalinterface implementeren.
type: docs
weight: 2480
url: /nl/net/aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

De ElementTraversal-interface is een set alleen-lezen attributen waarmee een auteur gemakkelijk tussen elementen in een document kan navigeren. Bij conforme implementaties van Element Traversal moeten alle objecten die Element implementeren ook de ElementTraversal-interface implementeren.

```csharp
public interface IElementTraversal
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom.traversal/ielementtraversal/childelementcount/) { get; } | Retourneert het huidige aantal elementknooppunten dat kinderen zijn van dit element. 0 als dit element geen onderliggende knooppunten heeft die van nodeType 1. zijn |
| [FirstElementChild](../../aspose.html.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Retourneert het eerste onderliggende elementknooppunt van dit element. null als dit element geen onderliggende elementen heeft. |
| [LastElementChild](../../aspose.html.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Geeft het laatste onderliggende elementknooppunt van dit element terug. null als dit element geen onderliggende elementen heeft. |
| [NextElementSibling](../../aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Retourneert het volgende elementknooppunt van dit element. null als dit element geen element-zusterknooppunten heeft die na dit element in de documentstructuur komen. |
| [PreviousElementSibling](../../aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Retourneert het vorige elementknooppunt van dit element. null als dit element geen element-zusterknooppunten heeft die vóór dit element in de documentstructuur komen. |

### Zie ook

* naamruimte [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* montage [Aspose.HTML](../../)


