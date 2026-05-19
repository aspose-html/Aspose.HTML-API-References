---
title: "Node.InsertBefore"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Node. Метод insertBefore интерфейса Node вставляет узел перед ссылочным узлом как дочерний элемент указанного родительского узла"
type: docs

url: /ru/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

Метод insertBefore() интерфейса Node вставляет узел перед опорным узлом в качестве дочернего элемента указанного родительского узла.

Если указанный узел уже существует в документе, insertBefore() перемещает его из текущего положения в новое. (То есть он будет автоматически удалён из своего текущего родителя перед добавлением к указанному новому родителю.)

Это означает, что узел не может находиться в двух местах документа одновременно.

```java
public Node InsertBefore(Node node, Node child)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | Node | Узел, который будет вставлен. |
| дочерний узел | Node | Узел, перед которым вставляется newNode. Если он равен null, newNode вставляется в конец дочерних узлов узла. |

### Возвращаемое значение

Возвращает добавленного дочернего узла (если newNode не является [`DocumentFragment`](../../documentfragment/); в противном случае возвращается пустой [`DocumentFragment`](../../documentfragment/)).

### См. также

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
