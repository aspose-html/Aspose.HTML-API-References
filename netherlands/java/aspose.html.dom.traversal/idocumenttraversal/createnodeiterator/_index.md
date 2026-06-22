---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IDocumentTraversal method. Maak een nieuwe NodeIterator over de subboom die is geworteld bij het opgegeven knooppunt."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Maak een nieuwe NodeIterator over de subboom die is geworteld bij het opgegeven knooppunt.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knooppunt dat samen met zijn kinderen zal worden doorlopen. De iterator wordt aanvankelijk gepositioneerd direct vóór dit knooppunt. De whatToShow-vlaggen en het filter, indien aanwezig, worden niet in aanmerking genomen bij het instellen van deze positie. De root mag niet null zijn. |

### Retourwaarde

De nieuw aangemaakte NodeIterator.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Maak een nieuwe NodeIterator over de subboom die is geworteld bij het opgegeven knooppunt.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knooppunt dat samen met zijn kinderen zal worden doorlopen. De iterator wordt aanvankelijk gepositioneerd direct vóór dit knooppunt. De whatToShow-vlaggen en het filter, indien aanwezig, worden niet in aanmerking genomen bij het instellen van deze positie. De root mag niet null zijn. |
| whatToShow | Int64 | vlag geeft aan welke knooptypen kunnen verschijnen in de logische weergave van de boom die door de iterator wordt gepresenteerd. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |

### Retourwaarde

De nieuw aangemaakte NodeIterator.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Maak een nieuwe NodeIterator over de subboom die is geworteld bij het opgegeven knooppunt.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knooppunt dat samen met zijn kinderen zal worden doorlopen. De iterator wordt aanvankelijk gepositioneerd direct vóór dit knooppunt. De whatToShow-vlaggen en het filter, indien aanwezig, worden niet in aanmerking genomen bij het instellen van deze positie. De root mag niet null zijn. |
| whatToShow | Int64 | vlag geeft aan welke knooptypen kunnen verschijnen in de logische weergave van de boom die door de iterator wordt gepresenteerd. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |
| filter | INodeFilter | NodeFilter die gebruikt wordt met deze TreeWalker, of null om aan te geven dat er geen filter is. |

### Retourwaarde

De nieuw aangemaakte NodeIterator.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
