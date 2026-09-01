---
title: "Node.CloneNode"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Node. Метод cloneNode интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет."
type: docs

url: /ru/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

Метод cloneNode() интерфейса Node возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет.

Клонирование узла копирует все его атрибуты и их значения, включая встроенные (inline) слушатели. Оно не копирует слушатели событий, добавленные с помощью [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) или назначенные свойствам элемента (например, node.onclick = someFunction). Кроме того, для элемента [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/) нарисованное изображение не копируется.

```java
public Node CloneNode()
```

### Возвращаемое значение

Новый [`Node`](../) клонирован. Клонированный узел не имеет родителя и не является частью документа, пока он не будет добавлен к другому узлу, который является частью документа, с помощью [`Node.appendChild()`](../appendchild/) или аналогичного метода.

### См. также

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

Метод cloneNode() интерфейса Node возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет.

Клонирование узла копирует все его атрибуты и их значения, включая встроенные (inline) слушатели. Оно не копирует слушатели событий, добавленные с помощью [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) или назначенные свойствам элемента (например, node.onclick = someFunction). Кроме того, для элемента [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement) нарисованное изображение не копируется.

```java
public Node CloneNode(bool deep)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | Boolean | Если true, то узел и всё его поддерево, включая текст, который может находиться в дочерних узлах [`Text`](../../text/), также копируются. |

### Возвращаемое значение

Новый [Node](T:com.aspose.html.dom.Node) клонирован. Клонированный узел не имеет родителя и не является частью документа, пока он не будет добавлен к другому узлу, который является частью документа, с помощью [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) или аналогичного метода.

### См. также

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
