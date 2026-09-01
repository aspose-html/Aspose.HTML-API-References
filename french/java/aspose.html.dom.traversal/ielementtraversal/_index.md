---
title: "Interface IElementTraversal"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.traversal.IElementTraversal. L'interface ElementTraversal est un ensemble d'attributs en lecture seule qui permettent à un auteur de naviguer facilement entre les éléments d'un document. Dans les implémentations conformes de Element Traversal, tous les objets qui implémentent Element doivent également implémenter l'interface ElementTraversal."
type: docs

url: /fr/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

L'interface ElementTraversal est un ensemble d'attributs en lecture seule qui permettent à un auteur de naviguer facilement entre les éléments d'un document. Dans les implémentations conformes de Element Traversal, tous les objets qui implémentent Element doivent également implémenter l'interface ElementTraversal.

```java
public interface IElementTraversal
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) Renvoie le nombre actuel de nœuds élément qui sont enfants de cet élément. 0 si cet élément n'a aucun nœud enfant de type nodeType 1. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) Renvoie le premier nœud élément enfant de cet élément. null si cet élément n'a aucun élément enfant. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) Renvoie le dernier nœud élément enfant de cet élément. null si cet élément n'a aucun élément enfant. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) Renvoie le nœud élément frère suivant de cet élément. null si cet élément n'a aucun nœud frère élément qui suit celui‑ci dans l'arbre du document. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) Renvoie le nœud élément frère précédent de cet élément. null si cet élément n'a aucun nœud frère élément qui précède celui‑ci dans l'arbre du document. |

### Voir aussi

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
