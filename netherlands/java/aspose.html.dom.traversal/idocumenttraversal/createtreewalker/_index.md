---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IDocumentTraversal-methode. Maak een nieuwe TreeWalker over de subboom die is geworteld in het opgegeven knooppunt."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Maak een nieuwe TreeWalker aan over de subboom die is geworteld bij het opgegeven knooppunt.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knooppunt dat zal dienen als de root voor de TreeWalker. De whatToShow‑vlaggen en de NodeFilter worden bij het instellen van deze waarde niet in aanmerking genomen; elk knooptype wordt geaccepteerd als root. Het currentNode van de TreeWalker wordt op dit knooppunt geïnitialiseerd, ongeacht of het zichtbaar is. De root fungeert als een stoppunt voor traversalmethoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De root mag niet null zijn. |

### Retourwaarde

De nieuw aangemaakte TreeWalker.

### Zie ook

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Maak een nieuwe TreeWalker aan over de subboom die is geworteld bij het opgegeven knooppunt.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knooppunt dat zal dienen als de root voor de TreeWalker. De whatToShow‑vlaggen en de NodeFilter worden bij het instellen van deze waarde niet in aanmerking genomen; elk knooptype wordt geaccepteerd als root. Het currentNode van de TreeWalker wordt op dit knooppunt geïnitialiseerd, ongeacht of het zichtbaar is. De root fungeert als een stoppunt voor traversalmethoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De root mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooptypen mogen verschijnen in de logische weergave van de boom die wordt gepresenteerd door de tree-walker. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |

### Retourwaarde

De nieuw aangemaakte TreeWalker.

### Zie ook

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Maak een nieuwe TreeWalker aan over de subboom die is geworteld bij het opgegeven knooppunt.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knooppunt dat zal dienen als de root voor de TreeWalker. De whatToShow‑vlaggen en de NodeFilter worden bij het instellen van deze waarde niet in aanmerking genomen; elk knooptype wordt geaccepteerd als root. Het currentNode van de TreeWalker wordt op dit knooppunt geïnitialiseerd, ongeacht of het zichtbaar is. De root fungeert als een stoppunt voor traversalmethoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De root mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooptypen mogen verschijnen in de logische weergave van de boom die wordt gepresenteerd door de tree-walker. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |
| filter | INodeFilter | NodeFilter die moet worden gebruikt met deze TreeWalker, of null om aan te geven dat er geen filter is. |

### Retourwaarde

De nieuw aangemaakte TreeWalker.

### Zie ook

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
