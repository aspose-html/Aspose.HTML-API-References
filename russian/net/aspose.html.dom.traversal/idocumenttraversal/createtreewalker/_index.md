---
title: CreateTreeWalker
second_title: Справочник по Aspose.HTML для .NET API
description: Создать новый TreeWalker поверх поддерева с корнем в указанном узле .
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
| root | Node | узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от того, виден он или нет. Корень функционирует как точка остановки для обхода методов , которые смотрят вверх в структуре документа, таких как parentNode и nextNode. Корень должен не быть нулевым. |

### Возвращаемое значение

Недавно созданный TreeWalker.

### Смотрите также

* interface [ITreeWalker](../../itreewalker)
* class [Node](../../../aspose.html.dom/node)
* interface [IDocumentTraversal](../../idocumenttraversal)
* пространство имен [Aspose.Html.Dom.Traversal](../../idocumenttraversal)
* сборка [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Создать новый TreeWalker поверх поддерева с корнем в указанном узле .

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| root | Node | узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от того, виден он или нет. Корень функционирует как точка остановки для обхода методов , которые смотрят вверх в структуре документа, таких как parentNode и nextNode. Корень должен не быть нулевым. |
| whatToShow | Int64 | флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, представляемого обходчиком дерева. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью ИЛИ. |

### Возвращаемое значение

Недавно созданный TreeWalker.

### Смотрите также

* interface [ITreeWalker](../../itreewalker)
* class [Node](../../../aspose.html.dom/node)
* interface [IDocumentTraversal](../../idocumenttraversal)
* пространство имен [Aspose.Html.Dom.Traversal](../../idocumenttraversal)
* сборка [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Создать новый TreeWalker поверх поддерева с корнем в указанном узле .

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| root | Node | узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от того, виден он или нет. Корень функционирует как точка остановки для обхода методов , которые смотрят вверх в структуре документа, таких как parentNode и nextNode. Корень должен не быть нулевым. |
| whatToShow | Int64 | флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, представляемого обходчиком дерева. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью ИЛИ. |
| filter | INodeFilter | NodeFilter для использования с этим TreeWalker, или нуль, чтобы указать отсутствие фильтра. |

### Возвращаемое значение

Недавно созданный TreeWalker.

### Смотрите также

* interface [ITreeWalker](../../itreewalker)
* class [Node](../../../aspose.html.dom/node)
* interface [INodeFilter](../../inodefilter)
* interface [IDocumentTraversal](../../idocumenttraversal)
* пространство имен [Aspose.Html.Dom.Traversal](../../idocumenttraversal)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
