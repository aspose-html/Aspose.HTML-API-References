---
title: "Document.CreateTreeWalker"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. Создает новый TreeWalker над поддеревом, корнем которого является указанный узел"
type: docs

url: /ru/java/com.aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Создайте новый TreeWalker над поддеревом, корнем которого является указанный узел.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Node | Узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от того, видим он или нет. Корень служит точкой остановки для методов обхода, которые поднимаются вверх по структуре документа, таких как parentNode и nextNode. Корень не должен быть null. |

### Возвращаемое значение

Новосозданный TreeWalker.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Создайте новый TreeWalker над поддеревом, корнем которого является указанный узел.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Node | Узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от того, видим он или нет. Корень служит точкой остановки для методов обхода, которые поднимаются вверх по структуре документа, таких как parentNode и nextNode. Корень не должен быть null. |
| whatToShow | Int64 | Флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, представленного обходчиком дерева. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью OR. |

### Возвращаемое значение

Новосозданный TreeWalker.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Создайте новый TreeWalker над поддеревом, корнем которого является указанный узел.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Node | Узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от того, видим он или нет. Корень служит точкой остановки для методов обхода, которые поднимаются вверх по структуре документа, таких как parentNode и nextNode. Корень не должен быть null. |
| whatToShow | Int64 | Флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, представленного обходчиком дерева. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью OR. |
| фильтр | INodeFilter | NodeFilter, используемый с этим TreeWalker, или null, указывающий отсутствие фильтра. |

### Возвращаемое значение

Новосозданный TreeWalker.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
