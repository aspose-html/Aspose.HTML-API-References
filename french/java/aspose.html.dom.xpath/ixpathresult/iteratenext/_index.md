---
title: "IXPathResult.IterateNext"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "IXPathResult method. Parcourt et renvoie le nœud suivant du jeu de nœuds ou `null` s'il n'y a plus de nœuds"
type: docs

url: /fr/java/com.aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Itère et renvoie le nœud suivant de l'ensemble de nœuds ou `null` s'il n'y a plus de nœuds.

```java
public Node IterateNext()
```

### Valeur de retour

Renvoie le nœud suivant.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR : levé si `resultType` n'est pas de type `UnorderedNodeIterator` ou `OrderedNodeIterator`. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR : Le document a été modifié depuis que le résultat a été renvoyé. |

### Voir aussi

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
