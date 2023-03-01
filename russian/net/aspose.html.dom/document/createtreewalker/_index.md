---
title: Document.CreateTreeWalker
second_title: Справочник по Aspose.HTML для .NET API
description: Document метод. Создать новый TreeWalker поверх поддерева с корнем в указанном узле .
type: docs
weight: 940
url: /ru/net/aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Создать новый TreeWalker поверх поддерева с корнем в указанном узле .

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| root | Node | node, который будет служить корнем для the TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. Текущий узел TreeWalker инициализируется этим узлом независимо от того, виден он или нет. Корень функционирует как точка остановки для методов traversal , которые смотрят вверх в структуре документа, таких как parentNode и nextNode. Корень must не должен быть нулевым. |

### Возвращаемое значение

Недавно созданный TreeWalker.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень is null. |

### Смотрите также

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Создать новый TreeWalker поверх поддерева с корнем в указанном узле .

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| root | Node | node, который будет служить корнем для the TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. Текущий узел TreeWalker инициализируется этим узлом независимо от того, виден он или нет. Корень функционирует как точка остановки для методов traversal , которые смотрят вверх в структуре документа, таких как parentNode и nextNode. Корень must не должен быть нулевым. |
| whatToShow | Int64 | флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, представленного обходчиком дерева. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью оператора ИЛИ. |

### Возвращаемое значение

Недавно созданный TreeWalker.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень is null. |

### Смотрите также

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Создать новый TreeWalker поверх поддерева с корнем в указанном узле .

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| root | Node | node, который будет служить корнем для the TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. Текущий узел TreeWalker инициализируется этим узлом независимо от того, виден он или нет. Корень функционирует как точка остановки для методов traversal , которые смотрят вверх в структуре документа, таких как parentNode и nextNode. Корень must не должен быть нулевым. |
| whatToShow | Int64 | флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, представленного обходчиком дерева. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью оператора ИЛИ. |
| filter | INodeFilter | NodeFilter для использования с this TreeWalker или null, чтобы указать отсутствие фильтра. |

### Возвращаемое значение

Недавно созданный TreeWalker.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень is null. |

### Смотрите также

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)


