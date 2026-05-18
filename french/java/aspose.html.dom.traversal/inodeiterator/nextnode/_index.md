---
title: "INodeIterator.NextNode"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode INodeIterator. Retourne le nœud suivant dans l'ensemble et avance la position de l'itérateur dans l'ensemble. Après la création d'un NodeIterator, le premier appel à nextNode renvoie le premier nœud de l'ensemble."
type: docs

url: /fr/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Renvoie le nœud suivant dans l'ensemble et avance la position de l'itérateur dans l'ensemble. Après la création d'un NodeIterator, le premier appel à nextNode() renvoie le premier nœud de l'ensemble.

```java
public Node NextNode()
```

### Valeur de retour

Le nœud suivant dans l'ensemble parcouru, ou null s'il n'y a plus de membres dans cet ensemble.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR : levée si cette méthode est appelée après l'invocation de la méthode detach. |

### Voir aussi

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
