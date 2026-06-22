---
title: "Класс NodeFilter"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.traversal.filters.NodeFilter. Фильтры — это объекты, которые умеют отфильтровывать узлы"
type: docs

url: /ru/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Фильтры — это объекты, которые умеют «отфильтровывать» узлы.

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Методы

| Имя | Описание |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Проверьте, видим ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно её не вызывают напрямую из пользовательского кода. (Хотя вы можете сделать это, если хотите использовать тот же фильтр для управления логикой вашего приложения.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Этот метод используется для получения типа объекта ECMAScript. |

## Поля

| Имя | Описание |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Принять узел. Навигационные методы, определённые для NodeIterator или TreeWalker, вернут этот узел. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Отклонить узел. Навигационные методы, определённые для NodeIterator или TreeWalker, не вернут этот узел. Для TreeWalker также будут отклонены дочерние узлы этого узла. NodeIterators рассматривают это как синоним FILTER_SKIP. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Пропустить этот отдельный узел. Навигационные методы, определённые для NodeIterator или TreeWalker, не вернут этот узел. Для обоих NodeIterator и TreeWalker дочерние узлы этого узла всё равно будут учитываться. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | Показать все узлы. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Показать узлы Attr. Это имеет смысл только при создании итератора или tree-walker с узлом-атрибутом в качестве корня; в этом случае атрибутный узел будет отображаться в первой позиции итерации или обхода. Поскольку атрибуты никогда не являются дочерними узлами других узлов, они не появляются при обходе дерева документа. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Показать узлы CDATASection. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Показать узлы Comment. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Показать узлы Document. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Показать узлы DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Показать узлы DocumentType. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Показать узлы Element. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Показать узлы Entity. Это имеет смысл только при создании итератора или tree-walker с узлом Entity в качестве корня; в этом случае узел Entity будет отображаться в первой позиции обхода. Поскольку сущности не являются частью дерева документа, они не появляются при обходе дерева документа. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Показать узлы EntityReference. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Показать узлы Notation. Это имеет смысл только при создании итератора или tree-walker с узлом Notation в качестве корня; в этом случае узел Notation будет находиться в первой позиции обхода. Поскольку нотации не являются частью дерева документа, они не появляются при обходе дерева документа. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Показать узлы ProcessingInstruction. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Показать узлы Text. |

### См. также

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
