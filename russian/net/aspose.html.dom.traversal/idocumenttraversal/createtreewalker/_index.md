---
title: IDocumentTraversal.CreateTreeWalker
second_title: Справочник по Aspose.HTML для .NET API
description: IDocumentTraversal метод. Создать новый TreeWalker поверх поддерева с корнем в указанном узле .
type: docs
weight: 20
url: /ru/net/aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
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

### Смотрите также

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* пространство имен [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
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

### Смотрите также

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* пространство имен [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
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

### Смотрите также

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* пространство имен [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* сборка [Aspose.HTML](../../../)


