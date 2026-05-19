---
title: "NodeListT Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.toolkit.markdown.syntax.NodeList1T класс. Базовая реализация NodeList"
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
| abstract [getCount](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/count/) Возвращает количество узлов в списке. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [Get](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | Возвращает узел по указанному индексу. |
| abstract [GetEnumerator](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | Возвращает узлы в коллекции. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | Записать узлы в текстовый писатель. |

### См. также

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
