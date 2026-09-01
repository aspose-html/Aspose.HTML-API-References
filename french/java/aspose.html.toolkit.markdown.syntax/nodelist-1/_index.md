---
title: "Classe NodeListT"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.toolkit.markdown.syntax.NodeList1T. Implémentation de base de la NodeList"
type: docs

url: /fr/java/com.aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

Implémentation de base de la NodeList.

```java
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| Paramètre | Description |
| --- | --- |
| T | Le type T. |

## Propriétés

| Nom | Description |
| --- | --- |
| abstract [getCount](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/count/) Obtient le nombre de nœuds dans la liste. |

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [Get](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | Obtient l'élément à l'index indiqué. |
| abstract [GetEnumerator](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | Obtient les éléments de la collection. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | Écrire les nœuds dans l'écrivain de texte. |

### Voir aussi

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
