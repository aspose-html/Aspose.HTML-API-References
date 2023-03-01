---
title: Interface IElementTraversal
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Traversal.IElementTraversal interface. Linterface ElementTraversal est un ensemble dattributs en lecture seule qui permettent à un auteur de naviguer facilement entre les éléments dun document. Dans les implémentations conformes dElement Traversal tous les objets qui implémentent Element doivent également implémenter linterface ElementTraversal.
type: docs
weight: 2480
url: /fr/net/aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

L'interface ElementTraversal est un ensemble d'attributs en lecture seule qui permettent à un auteur de naviguer facilement entre les éléments d'un document. Dans les implémentations conformes d'Element Traversal, tous les objets qui implémentent Element doivent également implémenter l'interface ElementTraversal.

```csharp
public interface IElementTraversal
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom.traversal/ielementtraversal/childelementcount/) { get; } | Renvoie le nombre actuel de nœuds d'élément qui sont des enfants de cet élément. 0 si cet élément n'a pas de nœuds enfants qui sont de nodeType 1. |
| [FirstElementChild](../../aspose.html.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Renvoie le premier nœud d'élément enfant de cet élément. null si cet élément n'a pas d'éléments enfants. |
| [LastElementChild](../../aspose.html.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Renvoie le dernier nœud d'élément enfant de cet élément. null si cet élément n'a pas d'éléments enfants. |
| [NextElementSibling](../../aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Renvoie le prochain nœud d'élément frère de cet élément. null si cet élément n'a aucun nœud frère d'élément qui vient après celui-ci dans l'arborescence du document. |
| [PreviousElementSibling](../../aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Renvoie le nœud d'élément frère précédent de cet élément. null si cet élément n'a aucun nœud frère d'élément qui précède celui-ci dans l'arborescence du document. |

### Voir également

* espace de noms [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* Assemblée [Aspose.HTML](../../)


