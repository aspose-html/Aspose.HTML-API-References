---
title: "NodeFilter.AcceptNode"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод NodeFilter. Проверить, видим ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно её не вызывают напрямую из пользовательского кода. Тем не менее вы можете сделать это, если хотите использовать тот же фильтр для управления логикой вашего приложения."
type: docs

url: /ru/java/com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Проверьте, видим ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно её не вызывают напрямую из пользовательского кода. (Хотя вы можете сделать это, если хотите использовать тот же фильтр для управления логикой вашего приложения.)

```java
public abstract short AcceptNode(Node n)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| n | Узел | узел, который проверяется на соответствие фильтру или нет. |

### Возвращаемое значение

константа, определяющая, принят ли узел, отклонён или пропущен, как указано выше.

### См. также

* class [Node](../../../com.aspose.html.dom/node/)
* class [NodeFilter](../)
* package [com.aspose.html.dom.traversal.filters](../../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../../)
