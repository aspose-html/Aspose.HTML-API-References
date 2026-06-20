---
title: "IXPathResult.SnapshotItem"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode IXPathResult. Renvoie l'élément d'indice index dans la collection d'instantanés. Si index est supérieur ou égal au nombre de nœuds dans la liste, cette méthode renvoie null. Contrairement au résultat d'itérateur, l'instantané ne devient pas invalide mais peut ne pas correspondre au document actuel s'il est modifié."
type: docs

url: /fr/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Renvoie l'élément `index`‑ème de la collection d'instantanés. Si `index` est supérieur ou égal au nombre de nœuds dans la liste, cette méthode renvoie `null`. Contrairement au résultat de l'itérateur, l'instantané ne devient pas invalide, mais il peut ne plus correspondre au document actuel s'il est modifié.

```java
public Node SnapshotItem(int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Indice dans la collection d'instantanés. |

### Valeur de retour

Le nœud à la position `index` dans le `NodeList`, ou `null` si cet indice n'est pas valide.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR : levée si `resultType` n’est pas de type `UnorderedNodeSnapshot` ou `OrderedNodeSnapshot`. |

### Voir aussi

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
