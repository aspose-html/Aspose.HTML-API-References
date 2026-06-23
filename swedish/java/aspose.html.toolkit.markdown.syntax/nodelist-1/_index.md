---
title: "NodeListT-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.toolkit.markdown.syntax.NodeList1T class. Basimplementation av NodeList"
type: docs

url: /sv/java/com.aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

Basimplementation av NodeList.

```java
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| Parameter | Beskrivning |
| --- | --- |
| T | T-typen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| abstract [getCount](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/count/) Hämtar antalet noder i listan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [Get](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | Hämtar noden på det angivna indexet. |
| abstract [GetEnumerator](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | Hämtar noderna i samlingen. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | Skriv noder till textskrivare. |

### Se även

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
