---
title: "Node.ReplaceChild"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Node. Заменяет дочерний узел oldChild на newChild в списке дочерних узлов и возвращает узел oldChild. Если newChild является объектом DocumentFragment, oldChild заменяется всеми дочерними узлами DocumentFragment, которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется."
type: docs

url: /ru/java/com.aspose.html.dom/node/replacechild/
---
## Node.ReplaceChild method

Заменяет дочерний узел oldChild на newChild в списке дочерних узлов и возвращает узел oldChild. Если newChild является объектом [`DocumentFragment`](../../documentfragment/), oldChild заменяется всеми дочерними узлами [`DocumentFragment`](../../documentfragment/), которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется.

```java
public Node ReplaceChild(Node node, Node child)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | Узел | Новый узел для замены oldChild. |
| дочерний элемент | Узел | Дочерний узел, который будет заменён. |

### Возвращаемое значение

Заменённый Node. Это тот же узел, что и oldChild.

### См. также

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
