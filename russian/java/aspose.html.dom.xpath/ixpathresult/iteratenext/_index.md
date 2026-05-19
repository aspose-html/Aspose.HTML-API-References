---
title: "IXPathResult.IterateNext"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод IXPathResult. Итерирует и возвращает следующий узел из набора узлов или null, если узлов больше нет."
type: docs

url: /ru/java/com.aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Итерирует и возвращает следующий узел из набора узлов или `null`, если узлов больше нет.

```java
public Node IterateNext()
```

### Возвращаемое значение

Возвращает следующий узел.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: возникает, если `resultType` не является типом `UnorderedNodeIterator` или `OrderedNodeIterator`. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: Документ был изменён после того, как результат был возвращён. |

### См. также

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
