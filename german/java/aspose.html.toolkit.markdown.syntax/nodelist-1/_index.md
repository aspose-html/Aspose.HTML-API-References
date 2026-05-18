---
title: "NodeListT Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.toolkit.markdown.syntax.NodeList1T Klasse. Basisimplementierung der NodeList."
type: docs

url: /de/java/com.aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

Basisimplementierung der NodeList.

```java
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| Parameter | Beschreibung |
| --- | --- |
| T | Der T-Typ. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [getCount](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/count/) Ermittelt die Anzahl der Knoten in der Liste. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [Get](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | Ermittelt das Element am angegebenen Index. |
| abstract [GetEnumerator](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | Ermittelt die Elemente in der Sammlung. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | Knoten in TextWriter schreiben. |

### Siehe auch

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
