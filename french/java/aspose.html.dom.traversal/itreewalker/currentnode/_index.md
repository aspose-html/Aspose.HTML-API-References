---
title: "ITreeWalker.CurrentNode"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété ITreeWalker. Le nœud auquel le TreeWalker est actuellement positionné. Des modifications de l'arbre DOM peuvent faire en sorte que le nœud actuel ne soit plus accepté par le filtre associé du TreeWalker. currentNode peut également être explicitement défini sur n'importe quel nœud, qu'il soit ou non dans le sous-arbre spécifié par le nœud racine ou qu'il serait accepté par le filtre et les drapeaux whatToShow. Un nouveau parcours se produit relativement à currentNode même s'il ne fait pas partie de la vue actuelle en appliquant les filtres dans la direction demandée ; si aucun parcours n'est possible, currentNode n'est pas modifié."
type: docs

url: /fr/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Le nœud auquel le TreeWalker est actuellement positionné. Des modifications de l'arbre DOM peuvent faire en sorte que le nœud actuel ne soit plus accepté par le filtre associé du TreeWalker. currentNode peut également être explicitement défini sur n'importe quel nœud, qu'il soit ou non dans le sous-arbre spécifié par le nœud racine ou qu'il serait accepté par le filtre et les drapeaux whatToShow. Un nouveau parcours se produit relativement à currentNode même s'il ne fait pas partie de la vue actuelle, en appliquant les filtres dans la direction demandée ; si aucun parcours n'est possible, currentNode n'est pas modifié.

```java
public Node CurrentNode { get; set; }
```

### Property Value

Le nœud actuel.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR : Levé si une tentative est faite de définir currentNode à null. |

### Voir aussi

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
