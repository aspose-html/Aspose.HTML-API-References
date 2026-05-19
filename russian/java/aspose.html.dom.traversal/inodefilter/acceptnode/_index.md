---
title: "INodeFilter.AcceptNode"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод INodeFilter. Проверяет, видим ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно её не вызывают напрямую из пользовательского кода. Тем не менее вы можете вызвать её, если хотите использовать тот же фильтр для управления логикой вашего приложения."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Проверьте, видим ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно её не вызывают напрямую из пользовательского кода. (Хотя вы можете сделать это, если хотите использовать тот же фильтр для управления логикой вашего приложения.)

```java
public short AcceptNode(Node n)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| n | Node | узел, который проверяется на соответствие фильтру. |

### Возвращаемое значение

константа, определяющая, принят ли узел, отклонён или пропущен, как описано выше.

### См. также

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
