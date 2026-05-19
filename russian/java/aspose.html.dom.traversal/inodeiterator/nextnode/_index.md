---
title: "INodeIterator.NextNode"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод INodeIterator. Возвращает следующий узел в наборе и перемещает позицию итератора вперед в наборе. После создания NodeIterator первый вызов nextNode возвращает первый узел в наборе."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Возвращает следующий узел в наборе и перемещает позицию итератора вперёд в наборе. После создания NodeIterator первый вызов nextNode() возвращает первый узел в наборе.

```java
public Node NextNode()
```

### Возвращаемое значение

Следующий узел в наборе, по которому происходит итерация, или null, если в этом наборе больше нет элементов.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: Возникает, если этот метод вызывается после того, как был вызван метод detach. |

### См. также

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
