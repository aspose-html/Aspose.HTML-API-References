---
title: "com.aspose.html.dom"
second_title: "Справочник API Aspose.HTML для Java"
description: "Пакет com.aspose.html.dom Document Object Model предоставляет API, представляющий и взаимодействующий с любыми документами HTML, XML или SVG. DOM — это модель документа, загружаемая в браузере и представляющая документ в виде дерева узлов, где каждый узел представляет часть документа, например элемент, текст, строку или комментарий."
type: docs

url: /ru/java/com.aspose.html.dom/
---
Пакет **com.aspose.html.dom (Document Object Model)** предоставляет API, представляющий и взаимодействующий с любыми документами HTML, XML или SVG. DOM — это модель документа, загружаемая в браузере и представляющая документ в виде дерева узлов, где каждый узел соответствует части документа (например, элементу, строке текста или комментарию).

## Классы

| Класс | Описание |
| --- | --- |
| [Attr](./attr/) | Интерфейс Attr представляет атрибут в объекте Element. Обычно допустимые значения атрибута определяются в схеме, связанной с документом. |
| [CDATASection](./cdatasection/) | Разделы CDATA используются для экранирования блоков текста, содержащих символы, которые в противном случае рассматривались бы как разметка. |
| [CharacterData](./characterdata/) | CharacterData расширяет Node набором атрибутов и методов для доступа к символьным данным в DOM. |
| [Comment](./comment/) | Наследуется от CharacterData и представляет содержимое комментария, то есть все символы между начальными ''. |
| [Document](./document/) | Document представляет весь документ HTML, XML или SVG. Концептуально это корень дерева документа и обеспечивает основной доступ к данным документа. |
| [DocumentFragment](./documentfragment/) | DocumentFragment — это "легковесный" или "минимальный" объект Document. Очень часто требуется возможность извлечь часть дерева документа или создать новый фрагмент документа. |
| [DocumentType](./documenttype/) | DocumentType предоставляет интерфейс к списку сущностей, определённых для документа. |
| [DOMException](./domexception/) | Интерфейс DOMException представляет аномальное событие (называемое исключением), которое происходит в результате вызова метода или доступа к свойству веб‑API. По сути, так описываются условия ошибок в веб‑API. |
| [DOMObject](./domobject/) | Тип DOMObject используется для представления базового объекта всей модели Document Object Model. Для Java и ECMAScript DOMObject привязан к типу Object. |
| [Element](./element/) | Интерфейс Element представляет элемент в документе HTML или XML. |
| [Entity](./entity/) | Представляет известную сущность, либо разобранную, либо неразобранную, в XML‑документе. |
| [EntityReference](./entityreference/) | Узлы EntityReference могут использоваться для представления ссылки на сущность в дереве. |
| [EventTarget](./eventtarget/) | Интерфейс EventTarget реализуется объектами, которые могут получать события и могут иметь слушатели для них. Другими словами, любой получатель событий реализует три метода, связанные с этим интерфейсом. |
| [Node](./node/) | Интерфейс Node является основным типом данных для всей модели Document Object Model. Он представляет один узел в дереве документа. Хотя все объекты, реализующие интерфейс Node, предоставляют методы для работы с дочерними элементами, не все такие объекты могут иметь дочерние элементы. Например, узлы [`Text`](../com.aspose.html.dom/text/) могут не иметь дочерних элементов, и попытка добавить дочерние элементы к таким узлам приводит к возникновению [`DOMException`](../com.aspose.html.dom/domexception/). |
| [Notation](./notation/) | Представляет обозначение, объявленное в DTD. |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction представляет «инструкцию обработки», используемую в XML как способ хранить специфичную для процессора информацию в тексте документа. |
| [QualifiedName](./qualifiedname/) | Представляет квалифицированное имя HTML. |
| [ShadowRoot](./shadowroot/) | ShadowRoot является корневым узлом теневого дерева. |
| [Text](./text/) | Интерфейс Text наследуется от CharacterData и представляет текстовое содержимое (именуемое символьными данными в XML) элемента Element или атрибута Attr. |
| [TypeInfo](./typeinfo/) | TypeInfo представляет тип, на который ссылаются узлы Element или Attr, указанный в схемах, связанных с документом. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Контекст просмотра — это среда, в которой объекты [`Document`](../com.aspose.html.dom/document/) отображаются пользователю. |
| [IChildNode](./ichildnode/) | Определяет интерфейс [`IChildNode`](../com.aspose.html.dom/ichildnode/), который должен быть реализован узлом [`Node`](../com.aspose.html.dom/node/), способным иметь родителя. |
| [IDOMImplementation](./idomimplementation/) | Интерфейс DOMImplementation предоставляет ряд методов для выполнения операций, независимых от конкретного экземпляра модели объектного документа. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Представляет интерфейс, который должен наследоваться всеми элементами, поддерживающими обработку системных событий. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Определяет [`IChildNode`](../com.aspose.html.dom/ichildnode/), которые не являются [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | Определяет [`IParentNode`](../com.aspose.html.dom/iparentnode/), которые не являются типом Element. |
| [IParentNode](./iparentnode/) | Определяет интерфейс [`IParentNode`](../com.aspose.html.dom/iparentnode/), реализуемый любыми возможными родителями. |
| [IStorage](./istorage/) | Этот интерфейс Web Storage API предоставляет доступ к сеансовому или локальному хранилищу конкретного домена. См. спецификацию Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Режимы, в которых ShadowRoot может работать. |
