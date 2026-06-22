---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод IDocumentTraversal. Создает новый NodeIterator для поддерева, корнем которого является указанный узел."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Создайте новый NodeIterator для поддерева, корнем которого является указанный узел.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Узел | Узел, который будет обходиться вместе со своими дочерними элементами. Итератор изначально позиционируется непосредственно перед этим узлом. Флаги whatToShow и фильтр, если они заданы, не учитываются при установке этой позиции. Корень не должен быть null. |

### Возвращаемое значение

Новосозданный NodeIterator.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Создайте новый NodeIterator для поддерева, корнем которого является указанный узел.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Узел | Узел, который будет обходиться вместе со своими дочерними элементами. Итератор изначально позиционируется непосредственно перед этим узлом. Флаги whatToShow и фильтр, если они заданы, не учитываются при установке этой позиции. Корень не должен быть null. |
| whatToShow | Int64 | Флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, предоставляемого итератором. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью OR. |

### Возвращаемое значение

Новосозданный NodeIterator.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Создайте новый NodeIterator для поддерева, корнем которого является указанный узел.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Узел | Узел, который будет обходиться вместе со своими дочерними элементами. Итератор изначально позиционируется непосредственно перед этим узлом. Флаги whatToShow и фильтр, если они заданы, не учитываются при установке этой позиции. Корень не должен быть null. |
| whatToShow | Int64 | Флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, предоставляемого итератором. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью OR. |
| фильтр | INodeFilter | NodeFilter, используемый с этим TreeWalker, или null, указывающий отсутствие фильтра. |

### Возвращаемое значение

Новосозданный NodeIterator.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
