---
title: "Interface ITreeWalker"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.traversal.ITreeWalker. Les objets TreeWalker sont utilisés pour naviguer dans un arbre ou sous‑arbre de document en utilisant la vue du document définie par leurs drapeaux whatToShow et, le cas échéant, le filtre. Toute fonction qui effectue une navigation à l’aide d’un TreeWalker supportera automatiquement toute vue définie par un TreeWalker."
type: docs

url: /fr/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

Les objets TreeWalker sont utilisés pour naviguer dans un arbre ou un sous-arbre de document en utilisant la vue du document définie par leurs drapeaux whatToShow et le filtre (le cas échéant). Toute fonction qui effectue une navigation à l'aide d'un TreeWalker supportera automatiquement toute vue définie par un TreeWalker.

Omettre des nœuds de la vue logique d’un sous‑arbre peut entraîner une structure sensiblement différente de celle du même sous‑arbre dans le document complet et non filtré. Les nœuds qui sont frères dans la vue TreeWalker peuvent être des enfants de nœuds différents, largement séparés, dans la vue originale. Par exemple, considérez un NodeFilter qui ignore tous les nœuds sauf les nœuds Text et le nœud racine d’un document. Dans la vue logique qui en résulte, tous les nœuds texte seront frères et apparaîtront comme enfants directs du nœud racine, quel que soit le niveau d’imbrication de la structure du document original.

Voir également la [Spécification du modèle d’objet Document (DOM) Niveau 2 – Traversal et Range](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## Propriétés

| Nom | Description |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## Méthodes

| Nom | Description |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | Déplace le TreeWalker vers le premier enfant visible du nœud actuel et renvoie le nouveau nœud. Si le nœud actuel n’a aucun enfant visible, renvoie null et conserve le nœud actuel. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | Déplace le TreeWalker vers le dernier enfant visible du nœud actuel et renvoie le nouveau nœud. Si le nœud actuel n’a aucun enfant visible, renvoie null et conserve le nœud actuel. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | Déplace le TreeWalker vers le nœud visible suivant dans l’ordre du document par rapport au nœud actuel et renvoie le nouveau nœud. Si le nœud actuel n’a pas de nœud suivant, ou si la recherche de nextNode tente de remonter depuis le nœud racine du TreeWalker, renvoie null et conserve le nœud actuel. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | Déplace le TreeWalker vers le frère suivant du nœud actuel et renvoie le nouveau nœud. Si le nœud actuel n’a pas de frère suivant visible, renvoie null et conserve le nœud actuel. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | Se déplace vers et renvoie le nœud ancêtre visible le plus proche du nœud actuel. Si la recherche de parentNode tente de remonter depuis le nœud racine du TreeWalker, ou si elle ne trouve pas d’ancêtre visible, cette méthode conserve la position actuelle et renvoie null. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | Déplace le TreeWalker vers le nœud visible précédent dans l'ordre du document par rapport au nœud actuel, et renvoie le nouveau nœud. Si le nœud actuel n'a pas de nœud précédent, ou si la recherche de previousNode tente de remonter depuis le nœud racine du TreeWalker, renvoie null et conserve le nœud actuel. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | Déplace le TreeWalker vers le frère précédent du nœud actuel, et renvoie le nouveau nœud. Si le nœud actuel n'a pas de frère précédent visible, renvoie null et conserve le nœud actuel. |

### Voir aussi

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
