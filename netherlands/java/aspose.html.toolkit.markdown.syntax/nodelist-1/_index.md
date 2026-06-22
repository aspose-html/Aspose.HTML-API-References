---
title: "NodeListT Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.toolkit.markdown.syntax.NodeList1T klasse. Basisimplementatie van de NodeList"
type: docs

url: /nl/java/com.aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

Basisimplementatie van de NodeList.

```java
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| Parameter | Beschrijving |
| --- | --- |
| T | Het T-type. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| abstract [getCount](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/count/) Haalt het aantal knooppunten in de lijst op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [Get](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | Haalt het node op de opgegeven index op. |
| abstract [GetEnumerator](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | Haalt de nodes in de collectie op. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | Schrijf knooppunten naar tekstschrijver. |

### Zie ook

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
