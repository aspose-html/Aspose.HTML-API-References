---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод IDocumentTraversal. Создает новый TreeWalker для поддерева, корнем которого является указанный узел."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Создайте новый TreeWalker для поддерева, корнем которого является указанный узел.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Узел | Узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от его видимости. Корень служит точкой остановки для методов обхода, которые поднимаются вверх по структуре документа, таких как parentNode и nextNode. Корень не должен быть null. |

### Возвращаемое значение

Новосозданный TreeWalker.

### См. также

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Создайте новый TreeWalker для поддерева, корнем которого является указанный узел.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Узел | Узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от его видимости. Корень служит точкой остановки для методов обхода, которые поднимаются вверх по структуре документа, таких как parentNode и nextNode. Корень не должен быть null. |
| whatToShow | Int64 | флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, предоставляемого обходчиком дерева. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью OR. |

### Возвращаемое значение

Новосозданный TreeWalker.

### См. также

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Создайте новый TreeWalker для поддерева, корнем которого является указанный узел.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Узел | Узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от его видимости. Корень служит точкой остановки для методов обхода, которые поднимаются вверх по структуре документа, таких как parentNode и nextNode. Корень не должен быть null. |
| whatToShow | Int64 | флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, предоставляемого обходчиком дерева. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью OR. |
| фильтр | INodeFilter | NodeFilter, используемый с этим TreeWalker, или null, указывающий отсутствие фильтра. |

### Возвращаемое значение

Новосозданный TreeWalker.

### См. также

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
