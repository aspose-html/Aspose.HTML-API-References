---
title: Document.CreateNodeIterator
second_title: Справочник по Aspose.HTML для .NET API
description: Document метод. Создать новый NodeIterator поверх поддерева с корнем в указанном узле .
type: docs
weight: 900
url: /ru/net/aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Создать новый NodeIterator поверх поддерева с корнем в указанном узле .

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| root | Node | узел, который будет повторяться вместе со своими дочерними элементами. Итератор изначально располагается непосредственно перед этим узлом. Флаги whatToShow и фильтр, если они есть, не учитываются при установке этой позиции. Корень не должен быть нулевым. |

### Возвращаемое значение

Недавно созданный NodeIterator.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень is null. |

### Смотрите также

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Создать новый NodeIterator поверх поддерева с корнем в указанном узле .

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| root | Node | узел, который будет повторяться вместе со своими дочерними элементами. Итератор изначально располагается непосредственно перед этим узлом. Флаги whatToShow и фильтр, если они есть, не учитываются при установке этой позиции. Корень не должен быть нулевым. |
| whatToShow | Int64 | флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, представляемого итератором. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью ИЛИ. |

### Возвращаемое значение

Недавно созданный NodeIterator.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень is null. |

### Смотрите также

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Создать новый NodeIterator поверх поддерева с корнем в указанном узле .

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| root | Node | узел, который будет повторяться вместе со своими дочерними элементами. Итератор изначально располагается непосредственно перед этим узлом. Флаги whatToShow и фильтр, если они есть, не учитываются при установке этой позиции. Корень не должен быть нулевым. |
| whatToShow | Int64 | флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, представляемого итератором. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью ИЛИ. |
| filter | INodeFilter | NodeFilter для использования с this TreeWalker или null, чтобы указать отсутствие фильтра. |

### Возвращаемое значение

Недавно созданный NodeIterator.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень is null. |

### Смотрите также

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)


