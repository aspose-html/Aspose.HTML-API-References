---
title: "HTMLTableSectionElement.DeleteRow"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "HTMLTableSectionElement méthode. Supprimer une ligne de cette section"
type: docs

url: /fr/java/com.aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

Supprimez une ligne de cette section.

```java
public void DeleteRow(int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | L'index de la ligne à supprimer, ou -1 pour supprimer la dernière ligne. Cet index commence à 0 et est relatif uniquement aux lignes contenues dans cette section, pas à toutes les lignes du tableau. |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR : Levée si l'index spécifié est supérieur ou égal au nombre de lignes ou si l'index est un nombre négatif autre que -1. @version DOM Level 2 |

### Voir aussi

* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
