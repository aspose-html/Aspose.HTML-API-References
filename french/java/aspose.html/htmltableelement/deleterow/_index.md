---
title: "HTMLTableElement.DeleteRow"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode HTMLTableElement. Supprime une ligne du tableau"
type: docs

url: /fr/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Supprime une ligne de tableau.

```java
public void DeleteRow(int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | L'index de la ligne à supprimer. Cet index commence à 0 et est relatif à l'ordre logique (et non à l'ordre du document) de toutes les lignes contenues dans le tableau. Si l'index est -1, la dernière ligne du tableau est supprimée. |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR : Levée si l'index spécifié est supérieur ou égal au nombre de lignes ou si l'index est un nombre négatif autre que -1. @version DOM Level 2 |

### Voir aussi

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
