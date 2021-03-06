---
title: NodeFilter
second_title: Справочник по Aspose.HTML для .NET API
description: Фильтры - это объекты умеющие отфильтровывать узлы.
type: docs
weight: 2570
url: /ru/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Фильтры - это объекты, умеющие "отфильтровывать" узлы.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Методы

| Имя | Описание |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode)(Node) | Проверить, виден ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно он не вызывается непосредственно из пользовательского кода. (Хотя вы могли бы сделать это, если бы хотели использовать тот же фильтр для управления собственной логикой приложения.) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype)() | Этот метод используется для получения объекта ECMAScriptType. |

## Поля

| Имя | Описание |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept) | Принять узел. Методы навигации, определенные для NodeIterator или TreeWalker, будут возвращать этот узел . |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject) | Отклонить узел. Методы навигации, определенные для NodeIterator или TreeWalker, не будут возвращать этот узел. Для TreeWalker дети этого узла также будут отклонены. Итераторы узлов рассматривают это как синоним для FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip) | Пропустить этот единственный узел. Методы навигации, определенные для NodeIterator или TreeWalker, не будут возвращать этот узел. И для NodeIterator, и для TreeWalker дочерние элементы этого узла по-прежнему будут учитываться . |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all) | Показать все узлы. |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute) | Показать узлы Attr. Это имеет смысл только при создании итератора или обходчика дерева с узлом атрибута в качестве его корня; в данном случае это означает, что узел атрибута появится в первой позиции итерации или обхода. Поскольку атрибуты никогда не являются потомками других узлов, они не появляются при обходе дерева документа. |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section) | Показать узлы CDATASection. |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment) | Показать узлы комментариев. |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document) | Показать узлы документа. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment) | Показать узлы DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type) | Показать узлы DocumentType. |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element) | Показать узлы элемента. |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity) | Показать узлы Entity. Это имеет смысл только при создании итератора или обходчика дерева с узлом Entity в качестве его корня; в данном случае это означает, что узел Entity появится в первой позиции обхода. Поскольку сущности не являются частью дерева документа, они не появляются при обходе по дереву документа. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference) | Показать узлы EntityReference. |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation) | Показать узлы нотации. Это имеет смысл только при создании итератора или обходчика дерева с узлом Notation в качестве его корня; в данном случае это означает, что узел Notation появится в первой позиции обхода . Поскольку нотации не являются частью дерева документа, они не появляются при переходе по дереву документа. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction) | Показать узлы ProcessingInstruction. |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text) | Показать узлы текста. |

### Смотрите также

* class [DOMObject](../../aspose.html.dom/domobject)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter)
* пространство имен [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
