---
title: ITreeWalker.CurrentNode
second_title: Справочник по Aspose.HTML для .NET API
description: ITreeWalker свойство. Узел в котором в данный момент расположен TreeWalker. Изменения в дереве DOM могут привести к тому что текущий узел больше не будет приниматься фильтром связанным с TreeWalker. currentNode также может быть явно установлен на любой узел независимо от того внутри поддерева заданного корневым узлом  или будет принят фильтром и флагами whatToShow. Дальнейший обход происходит относительно currentNode даже если он не является частью текущего представления путем применения фильтров в запрошенном направлении если обход невозможен currentNode не изменяется.
type: docs
weight: 10
url: /ru/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Узел, в котором в данный момент расположен TreeWalker. Изменения в дереве DOM могут привести к тому, что текущий узел больше не будет приниматься фильтром, связанным с TreeWalker. currentNode также может быть явно установлен на любой узел, независимо от того, внутри поддерева, заданного корневым узлом , или будет принят фильтром и флагами whatToShow. Дальнейший обход происходит относительно currentNode, даже если он не является частью текущего представления, путем применения фильтров в запрошенном направлении; если обход невозможен, currentNode не изменяется.

```csharp
public Node CurrentNode { get; set; }
```

### Стоимость имущества

Текущий узел.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает при попытке установить значение null для параметра currentNode. |

### Смотрите также

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* пространство имен [Aspose.Html.Dom.Traversal](../../itreewalker/)
* сборка [Aspose.HTML](../../../)


