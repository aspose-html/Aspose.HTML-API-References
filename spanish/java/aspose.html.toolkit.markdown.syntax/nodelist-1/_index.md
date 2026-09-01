---
title: "Clase NodeListT"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.toolkit.markdown.syntax.NodeList1T. Implementación base de la NodeList"
type: docs

url: /es/java/com.aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

Implementación base de NodeList.

```java
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| Parámetro | Descripción |
| --- | --- |
| T | El tipo T. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| abstract [getCount](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/count/) Obtiene el número de nodos en la lista. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [Get](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | Obtiene el nodo en el índice especificado. |
| abstract [GetEnumerator](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | Obtiene los nodos de la colección. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | Escribir nodos en el escritor de texto. |

### Ver también

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
