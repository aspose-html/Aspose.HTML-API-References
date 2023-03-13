---
title: ITreeWalker.CurrentNode
second_title: Référence de l'API Aspose.HTML pour .NET
description: ITreeWalker propriété. Le nœud sur lequel le TreeWalker est actuellement positionné. Les modifications apportées à larborescence DOM peuvent empêcher le nœud actuel dêtre accepté par le filtre associé du TreeWalker. currentNode peut également être explicitement défini sur nimporte quel nœud quil soit ou non dans le sousarbre spécifié par le nœud racine ou serait accepté par les indicateurs de filtre et whatToShow. Une traversée supplémentaire se produit par rapport à currentNode même sil ne fait pas partie de la vue actuelle en appliquant les filtres dans la direction demandée  si aucune traversée nest possible currentNode nest pas modifié.
type: docs
weight: 10
url: /fr/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Le nœud sur lequel le TreeWalker est actuellement positionné. Les modifications apportées à l'arborescence DOM peuvent empêcher le nœud actuel d'être accepté par le filtre associé du TreeWalker. currentNode peut également être explicitement défini sur n'importe quel nœud, qu'il soit ou non dans le sous-arbre spécifié par le nœud racine ou serait accepté par les indicateurs de filtre et whatToShow. Une traversée supplémentaire se produit par rapport à currentNode même s'il ne fait pas partie de la vue actuelle, en appliquant les filtres dans la direction demandée ; si aucune traversée n'est possible, currentNode n'est pas modifié.

```csharp
public Node CurrentNode { get; set; }
```

### Valeur de la propriété

Le nœud actuel.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR : déclenché si une tentative est faite pour définir currentNode sur null. |

### Voir également

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* espace de noms [Aspose.Html.Dom.Traversal](../../itreewalker/)
* Assemblée [Aspose.HTML](../../../)


