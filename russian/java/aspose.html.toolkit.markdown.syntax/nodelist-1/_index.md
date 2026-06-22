---
title: "Класс NodeListT"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.toolkit.markdown.syntax.NodeList1T. Базовая реализация NodeList"
type: docs

url: /ru/java/com.aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

Базовая реализация NodeList.

```java
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| Параметр | Описание |
| --- | --- |
| T | Тип T. |

## Свойства

| Имя | Описание |
| --- | --- |
| abstract [getCount](../../com.aspose.html.toolkit.syntax/nodelist-1/count/) Получает количество узлов в списке. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [Get](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | Получает узел по указанному индексу. |
| abstract [GetEnumerator](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | Получает узлы из коллекции. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | Записать узлы в текстовый writer. |

### См. также

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
