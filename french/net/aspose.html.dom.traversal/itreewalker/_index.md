---
title: Interface ITreeWalker
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Traversal.ITreeWalker interface. Les objets TreeWalker sont utilisés pour naviguer dans une arborescence de documents ou une sousarborescence en utilisant la vue du document définie par leurs drapeaux whatToShow et leur filtre le cas échéant. Toute fonction qui effectue la navigation à laide dun TreeWalker prendra automatiquement en charge toute vue définie par un TreeWalker.
type: docs
weight: 2520
url: /fr/net/aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

Les objets TreeWalker sont utilisés pour naviguer dans une arborescence de documents ou une sous-arborescence en utilisant la vue du document définie par leurs drapeaux whatToShow et leur filtre (le cas échéant). Toute fonction qui effectue la navigation à l'aide d'un TreeWalker prendra automatiquement en charge toute vue définie par un TreeWalker.

L'omission de nœuds de la vue logique d'une sous-arborescence peut entraîner une structure sensiblement différente de la même sous-arborescence dans le document complet et non filtré. Les nœuds qui sont frères dans la vue TreeWalker peuvent être des enfants de différents nœuds largement séparés dans la vue d'origine. Par exemple, considérez un NodeFilter qui ignore tous les nœuds à l'exception des nœuds de texte et le nœud racine d'un document. Dans la vue logique qui en résulte, tous les nœuds de texte seront frères et apparaîtront comme des enfants directs du nœud racine, peu importe la profondeur d'imbrication de la structure du document d'origine.

Voir aussi le[Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @depuis le niveau DOM 2

```csharp
public interface ITreeWalker : ITraversal
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CurrentNode](../../aspose.html.dom.traversal/itreewalker/currentnode/) { get; set; } | Le nœud sur lequel le TreeWalker est actuellement positionné. Les modifications apportées à l'arborescence DOM peuvent empêcher le nœud actuel d'être accepté par le filtre associé du TreeWalker. currentNode peut également être explicitement défini sur n'importe quel nœud, qu'il soit ou non dans le sous-arbre spécifié par le nœud racine ou serait accepté par les indicateurs de filtre et whatToShow. Une traversée supplémentaire se produit par rapport à currentNode même s'il ne fait pas partie de la vue actuelle, en appliquant les filtres dans la direction demandée ; si aucune traversée n'est possible, currentNode n'est pas modifié. |

## Méthodes

| Nom | La description |
| --- | --- |
| [FirstChild](../../aspose.html.dom.traversal/itreewalker/firstchild/)() | Déplace le TreeWalker vers le premier enfant visible du nœud actuel et renvoie le nouveau nœud. Si le nœud actuel n'a pas d'enfants visibles , renvoie null et conserve le nœud current . |
| [LastChild](../../aspose.html.dom.traversal/itreewalker/lastchild/)() | Déplace le TreeWalker vers le dernier enfant visible du nœud actuel et renvoie le nouveau nœud. Si le nœud actuel n'a pas d'enfants visibles , renvoie null et conserve le nœud current . |
| [NextNode](../../aspose.html.dom.traversal/itreewalker/nextnode/)() | Déplace le TreeWalker vers le nœud visible suivant dans l'ordre document par rapport au nœud actuel et renvoie le nouveau nœud. Si le nœud actuel n'a pas de nœud suivant, ou si la recherche de nextNode tente de remonter à partir du nœud root du TreeWalker, renvoie null et conserve le nœud actuel. |
| [NextSibling](../../aspose.html.dom.traversal/itreewalker/nextsibling/)() | Déplace le TreeWalker vers le frère suivant du nœud current et renvoie le nouveau nœud. Si le nœud actuel n'a pas de frère visible suivant, renvoie null et conserve le nœud actuel. |
| [ParentNode](../../aspose.html.dom.traversal/itreewalker/parentnode/)() | Déplace et renvoie le nœud ancêtre visible le plus proche du nœud actuel . Si la recherche de parentNode tente de monter par pas à partir du nœud racine du TreeWalker, ou si elle ne parvient pas à trouver un nœud ancêtre visible, cette méthode conserve la position actuelle et renvoie null. |
| [PreviousNode](../../aspose.html.dom.traversal/itreewalker/previousnode/)() | Déplace le TreeWalker vers le nœud visible précédent dans l'ordre du document par rapport au nœud actuel et renvoie le nouveau nœud . Si le nœud actuel n'a pas de nœud précédent, ou si la recherche de previousNode tente de remonter à partir du nœud racine du TreeWalker, renvoie null et conserve le nœud actuel. |
| [PreviousSibling](../../aspose.html.dom.traversal/itreewalker/previoussibling/)() | Déplace le TreeWalker vers le frère précédent du nœud actuel et renvoie le nouveau nœud. Si le nœud actuel n'a pas de frère précédent visible , renvoie null et conserve le nœud actuel . |

### Voir également

* interface [ITraversal](../itraversal/)
* espace de noms [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* Assemblée [Aspose.HTML](../../)


