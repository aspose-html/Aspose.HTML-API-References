---
title: "Node.RemoveChild"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Node. Метод removeChild интерфейса Node удаляет дочерний узел из DOM и возвращает удалённый узел"
type: docs

url: /ru/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

Метод removeChild() интерфейса Node удаляет дочерний узел из DOM и возвращает удалённый узел.

Примечание: Пока сохраняется ссылка на удалённый дочерний узел, он остаётся в памяти, но больше не является частью DOM. Его можно повторно использовать позже в коде. Если возвращаемое значение removeChild() не сохраняется и нет других ссылок, он будет автоматически удалён из памяти через короткое время.

```java
public Node RemoveChild(Node child)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| child | Node | Объект [`Node`](../), который является дочерним узлом, подлежащим удалению из DOM. |

### Возвращаемое значение

В отличие от [`Node.cloneNode()`](../clonenode/) возвращаемое значение сохраняет связанные с ним объекты [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/).

### См. также

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
