---
title: Document.CreateTreeWalker
second_title: Aspose.HTML voor .NET API-referentie
description: Document methode. Maak een nieuwe TreeWalker over de subboom die is geroot op het gespecificeerde knooppunt.
type: docs
weight: 940
url: /nl/net/aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Maak een nieuwe TreeWalker over de subboom die is geroot op het gespecificeerde knooppunt.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | node die zal dienen als de root voor the TreeWalker. De vlaggen whatToShow en de NodeFilter worden niet in aanmerking genomen bij het instellen van deze waarde; elk knooppunttype wordt geaccepteerd als de root. De currentNode van de TreeWalker is geïnitialiseerd op deze node, of deze nu zichtbaar is of niet. De root functioneert als een stoppunt voor traversal methoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De root mag niet null zijn. |

### Winstwaarde

De nieuw gecreëerde TreeWalker.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Verhoogd als de gespecificeerde root is null. |

### Zie ook

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* naamruimte [Aspose.Html.Dom](../../document/)
* montage [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Maak een nieuwe TreeWalker over de subboom die is geroot op het gespecificeerde knooppunt.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | node die zal dienen als de root voor the TreeWalker. De vlaggen whatToShow en de NodeFilter worden niet in aanmerking genomen bij het instellen van deze waarde; elk knooppunttype wordt geaccepteerd als de root. De currentNode van de TreeWalker is geïnitialiseerd op deze node, of deze nu zichtbaar is of niet. De root functioneert als een stoppunt voor traversal methoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De root mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooppunttypes mogen verschijnen in de logische weergave van de boom gepresenteerd door de boomloper. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |

### Winstwaarde

De nieuw gecreëerde TreeWalker.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Verhoogd als de gespecificeerde root is null. |

### Zie ook

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* naamruimte [Aspose.Html.Dom](../../document/)
* montage [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Maak een nieuwe TreeWalker over de subboom die is geroot op het gespecificeerde knooppunt.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | node die zal dienen als de root voor the TreeWalker. De vlaggen whatToShow en de NodeFilter worden niet in aanmerking genomen bij het instellen van deze waarde; elk knooppunttype wordt geaccepteerd als de root. De currentNode van de TreeWalker is geïnitialiseerd op deze node, of deze nu zichtbaar is of niet. De root functioneert als een stoppunt voor traversal methoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De root mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooppunttypes mogen verschijnen in de logische weergave van de boom gepresenteerd door de boomloper. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |
| filter | INodeFilter | NodeFilter te gebruiken met this TreeWalker, of null om aan te geven dat er geen filter is. |

### Winstwaarde

De nieuw gecreëerde TreeWalker.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Verhoogd als de gespecificeerde root is null. |

### Zie ook

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* naamruimte [Aspose.Html.Dom](../../document/)
* montage [Aspose.HTML](../../../)


