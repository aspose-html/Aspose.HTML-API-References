---
title: "Interface IDocumentTraversal"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.traversal.IDocumentTraversal. DocumentTraversal contient des méthodes qui créent des itérateurs et des tree-walkers pour parcourir un nœud et ses enfants dans l'ordre du document en profondeur d'abord, préordre, ce qui équivaut à l'ordre dans lequel les balises d'ouverture apparaissent dans la représentation textuelle du document. Dans les DOM qui prennent en charge la fonctionnalité Traversal, DocumentTraversal sera implémenté par les mêmes objets qui implémentent l'interface Document."
type: docs

url: /fr/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal contient des méthodes qui créent des itérateurs et des tree-walkers pour parcourir un nœud et ses enfants dans l'ordre du document (parcours en profondeur, pré-ordre, qui est équivalent à l'ordre dans lequel les balises d'ouverture apparaissent dans la représentation textuelle du document). Dans les DOM qui prennent en charge la fonctionnalité Traversal, DocumentTraversal sera implémenté par les mêmes objets qui implémentent l'interface Document.

Voir également le [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Méthodes

| Nom | Description |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Crée un nouveau NodeIterator sur le sous-arbre enraciné au nœud spécifié. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Crée un nouveau NodeIterator sur le sous-arbre enraciné au nœud spécifié. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Crée un nouveau NodeIterator sur le sous-arbre enraciné au nœud spécifié. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Crée un nouveau TreeWalker sur le sous-arbre enraciné au nœud spécifié. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Crée un nouveau TreeWalker sur le sous-arbre enraciné au nœud spécifié. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Crée un nouveau TreeWalker sur le sous-arbre enraciné au nœud spécifié. |

### Voir aussi

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
