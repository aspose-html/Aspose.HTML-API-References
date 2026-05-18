---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode IDocumentTraversal. Crée un nouveau NodeIterator sur le sous-arbre dont la racine est le nœud spécifié."
type: docs

url: /fr/java/com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Crée un nouveau NodeIterator sur le sous-arbre enraciné au nœud spécifié.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| racine | Node | nœud qui sera parcouru avec ses enfants. L'itérateur est initialement positionné juste avant ce nœud. Les indicateurs whatToShow et le filtre, le cas échéant, ne sont pas pris en compte lors du réglage de cette position. La racine ne doit pas être null. |

### Valeur de retour

Le NodeIterator nouvellement créé.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR : Levé si la racine spécifiée est null. |

### Voir aussi

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Crée un nouveau NodeIterator sur le sous-arbre enraciné au nœud spécifié.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| racine | Node | nœud qui sera parcouru avec ses enfants. L'itérateur est initialement positionné juste avant ce nœud. Les indicateurs whatToShow et le filtre, le cas échéant, ne sont pas pris en compte lors du réglage de cette position. La racine ne doit pas être null. |
| whatToShow | Int64 | drapeau qui indique quels types de nœuds peuvent apparaître dans la vue logique de l'arbre présenté par l'itérateur. Voir la description de NodeFilter pour l'ensemble des valeurs SHOW_ possibles. Ces drapeaux peuvent être combinés à l'aide de OR. |

### Valeur de retour

Le NodeIterator nouvellement créé.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR : Levé si la racine spécifiée est null. |

### Voir aussi

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Crée un nouveau NodeIterator sur le sous-arbre enraciné au nœud spécifié.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| racine | Node | nœud qui sera parcouru avec ses enfants. L'itérateur est initialement positionné juste avant ce nœud. Les indicateurs whatToShow et le filtre, le cas échéant, ne sont pas pris en compte lors du réglage de cette position. La racine ne doit pas être null. |
| whatToShow | Int64 | drapeau qui indique quels types de nœuds peuvent apparaître dans la vue logique de l'arbre présenté par l'itérateur. Voir la description de NodeFilter pour l'ensemble des valeurs SHOW_ possibles. Ces drapeaux peuvent être combinés à l'aide de OR. |
| filtre | INodeFilter | NodeFilter à utiliser avec ce TreeWalker, ou null pour indiquer aucun filtre. |

### Valeur de retour

Le NodeIterator nouvellement créé.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR : Levé si la racine spécifiée est null. |

### Voir aussi

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
