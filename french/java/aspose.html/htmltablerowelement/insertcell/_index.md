---
title: "HTMLTableRowElement.InsertCell"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode HTMLTableRowElement. Insère une cellule TD vide dans cette ligne. Si l'index est -1 ou égal au nombre de cellules, la nouvelle cellule est ajoutée à la fin"
type: docs

url: /fr/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Insérer une cellule vide `TD` dans cette ligne. Si `index` vaut -1 ou est égal au nombre de cellules, la nouvelle cellule est ajoutée à la fin.

```java
public HTMLElement InsertCell(int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | L'emplacement où insérer la cellule, à partir de 0. |

### Valeur de retour

La cellule nouvellement créée.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR : Levée si le `index` spécifié est supérieur au nombre de cellules ou si l'index est un nombre négatif autre que -1. @version DOM Level 2 |

### Voir aussi

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
