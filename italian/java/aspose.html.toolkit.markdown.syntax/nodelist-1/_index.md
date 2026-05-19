---
title: "Classe NodeListT"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.toolkit.markdown.syntax.NodeList1T. Implementazione di base del NodeList"
type: docs

url: /it/java/com.aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

Implementazione base della NodeList.

```java
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo T. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| abstract [getCount](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/count/) Ottiene il numero di nodi nella lista. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [Get](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | Ottiene l'elemento all'indice specificato. |
| abstract [GetEnumerator](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | Ottiene gli elementi nella collezione. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | Scrivi i nodi su un writer di testo. |

### Vedi anche

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
