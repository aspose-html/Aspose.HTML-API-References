---
title: IDocumentTraversal.CreateNodeIterator
second_title: Aspose.HTML voor .NET API-referentie
description: IDocumentTraversal methode. Maak een nieuwe NodeIterator over de substructuur die is geworteld in het gespecificeerde knooppunt.
type: docs
weight: 10
url: /nl/net/aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Maak een nieuwe NodeIterator over de substructuur die is geworteld in het gespecificeerde knooppunt.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | node die samen met zijn kinderen zal worden herhaald. De iterator bevindt zich aanvankelijk net voor deze node. De whatToShow-vlaggen en het filter, indien aanwezig, worden niet overwogen bij het instellen van deze positie. De root mag niet null zijn. |

### Winstwaarde

De nieuw gemaakte NodeIterator.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Verhoogd als de gespecificeerde root is null. |

### Zie ook

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* naamruimte [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* montage [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Maak een nieuwe NodeIterator over de substructuur die is geworteld in het gespecificeerde knooppunt.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | node die samen met zijn kinderen zal worden herhaald. De iterator bevindt zich aanvankelijk net voor deze node. De whatToShow-vlaggen en het filter, indien aanwezig, worden niet overwogen bij het instellen van deze positie. De root mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooppunttypes mogen verschijnen in de logische weergave van de boom gepresenteerd door de iterator. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |

### Winstwaarde

De nieuw gemaakte NodeIterator.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Verhoogd als de gespecificeerde root is null. |

### Zie ook

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* naamruimte [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* montage [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Maak een nieuwe NodeIterator over de substructuur die is geworteld in het gespecificeerde knooppunt.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | node die samen met zijn kinderen zal worden herhaald. De iterator bevindt zich aanvankelijk net voor deze node. De whatToShow-vlaggen en het filter, indien aanwezig, worden niet overwogen bij het instellen van deze positie. De root mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooppunttypes mogen verschijnen in de logische weergave van de boom gepresenteerd door de iterator. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |
| filter | INodeFilter | NodeFilter te gebruiken met this TreeWalker, of null om aan te geven dat er geen filter is. |

### Winstwaarde

De nieuw gemaakte NodeIterator.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Verhoogd als de gespecificeerde root is null. |

### Zie ook

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* naamruimte [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* montage [Aspose.HTML](../../../)


