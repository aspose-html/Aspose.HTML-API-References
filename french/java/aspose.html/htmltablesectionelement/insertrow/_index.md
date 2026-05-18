---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "HTMLTableSectionElement méthode. Insérer une ligne dans cette section. La nouvelle ligne est insérée immédiatement avant la ligne d'index actuel dans cette section. Si l'index est -1 ou égal au nombre de lignes de cette section, la nouvelle ligne est ajoutée à la fin"
type: docs

url: /fr/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Insérez une ligne dans cette section. La nouvelle ligne est insérée immédiatement avant la ligne `index`e actuelle de cette section. Si `index` vaut -1 ou est égal au nombre de lignes de cette section, la nouvelle ligne est ajoutée à la fin.

```java
public HTMLElement InsertRow(int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Le numéro de ligne où insérer une nouvelle ligne. Cet index commence à 0 et est relatif uniquement aux lignes contenues dans cette section, pas à toutes les lignes du tableau. |

### Valeur de retour

La ligne nouvellement créée.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Levée si l'index spécifié est supérieur au nombre de lignes ou si l'index est un nombre négatif autre que -1. @version DOM Level 2 |

### Voir aussi

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
