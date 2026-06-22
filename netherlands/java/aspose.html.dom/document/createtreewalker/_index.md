---
title: "Document.CreateTreeWalker"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Document-methode. Maak een nieuwe TreeWalker aan over de subboom die is geworteld bij het opgegeven knooppunt."
type: docs

url: /nl/java/com.aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Maak een nieuwe TreeWalker over de subboom die is geworteld bij het opgegeven knooppunt.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knooppunt dat zal dienen als de root voor de TreeWalker. De whatToShow-vlaggen en de NodeFilter worden niet in aanmerking genomen bij het instellen van deze waarde; elk knooptype wordt geaccepteerd als root. De currentNode van de TreeWalker wordt op dit knooppunt geïnitialiseerd, ongeacht of het zichtbaar is. De root fungeert als een stoppunt voor traversalmethoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De root mag niet null zijn. |

### Retourwaarde

De nieuw aangemaakte TreeWalker.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Maak een nieuwe TreeWalker over de subboom die is geworteld bij het opgegeven knooppunt.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knooppunt dat zal dienen als de root voor de TreeWalker. De whatToShow-vlaggen en de NodeFilter worden niet in aanmerking genomen bij het instellen van deze waarde; elk knooptype wordt geaccepteerd als root. De currentNode van de TreeWalker wordt op dit knooppunt geïnitialiseerd, ongeacht of het zichtbaar is. De root fungeert als een stoppunt voor traversalmethoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De root mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooptypen kunnen verschijnen in de logische weergave van de boom die wordt gepresenteerd door de tree-walker. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |

### Retourwaarde

De nieuw aangemaakte TreeWalker.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Maak een nieuwe TreeWalker over de subboom die is geworteld bij het opgegeven knooppunt.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knooppunt dat zal dienen als de root voor de TreeWalker. De whatToShow-vlaggen en de NodeFilter worden niet in aanmerking genomen bij het instellen van deze waarde; elk knooptype wordt geaccepteerd als root. De currentNode van de TreeWalker wordt op dit knooppunt geïnitialiseerd, ongeacht of het zichtbaar is. De root fungeert als een stoppunt voor traversalmethoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De root mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooptypen kunnen verschijnen in de logische weergave van de boom die wordt gepresenteerd door de tree-walker. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |
| filter | INodeFilter | NodeFilter die gebruikt wordt met deze TreeWalker, of null om aan te geven dat er geen filter is. |

### Retourwaarde

De nieuw aangemaakte TreeWalker.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
