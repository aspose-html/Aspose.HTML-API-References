---
title: Class NodeFilter
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Traversal.Filters.NodeFilter сорт. Фильтры  это объекты умеющие отфильтровывать узлы.
type: docs
weight: 2460
url: /ru/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Фильтры — это объекты, умеющие «отфильтровывать» узлы.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Методы

| Имя | Описание |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Проверить, виден ли указанный узел в логическом представлении a TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно он не вызывается напрямую из кода пользователя from . (Хотя вы могли бы сделать это, если бы хотели использовать фильтр same для управления логикой вашего собственного приложения.) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |

## Поля

| Имя | Описание |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Принять узел. Методы навигации, определенные для NodeIterator или TreeWalker, вернут этот узел . |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Отклонить узел. Методы навигации, определенные для NodeIterator или TreeWalker, не будут возвращать этот узел. Для TreeWalker дочерние элементы этого узла также будут отклонены. NodeIterators рассматривает это как синоним для FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Пропустить этот единственный узел. Методы навигации, определенные для NodeIterator или TreeWalker, не будут возвращать этот узел. И для NodeIterator, и для TreeWalker дочерние узлы этого узла по-прежнему будут считаться . |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all/) | Показать все узлы. |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Показать узлы Attr. Это имеет смысл только при создании итератора или обходчика по дереву с узлом атрибута в качестве корня ; в данном случае это означает, что узел атрибута появится в первой позиции итерации или обхода. Поскольку атрибуты никогда не являются потомками других узлов, они не появляются при обходе дерева документа. |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Показать узлы CDATASection. |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Показать узлы комментариев. |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document/) | Показать узлы документа. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Показать узлы DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Показать узлы типа документа. |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element/) | Показать узлы элементов. |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Показать узлы Entity. Это имеет смысл только при создании итератора или обходчика дерева с узлом Entity в качестве корня ; в данном случае это означает, что узел Entity появится в первой позиции обхода. Поскольку объекты не являются частью дерева документа, они не отображаются, когда перемещается по дереву документа. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Показать узлы EntityReference. |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Показать узлы нотации. Это имеет смысл только при создании итератора или обходчика дерева с узлом Notation в качестве корня ; в данном случае это означает, что узел Notation появится в первой позиции обхода . Поскольку нотации не являются частью дерева документа, они не отображаются при переходе по дереву документа. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Показать узлы ProcessingInstruction. |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text/) | Показать узлы текста. |

### Смотрите также

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter/)
* пространство имен [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters/)
* сборка [Aspose.HTML](../../)


