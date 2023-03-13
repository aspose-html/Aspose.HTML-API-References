---
title: Aspose.Html.Dom
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom объектная модель документа namespace предоставляет API который представляет любые документы HTML XML или SVG и взаимодействует с ними. DOM  это модель документа загруженная в браузер и представляет документ в виде дерева узлов где каждый node представляет часть документа например элемент текст строка или комментарий.
type: docs
weight: 40
url: /ru/net/aspose.html.dom/
---
**Aspose.Html.Dom (объектная модель документа)** namespace предоставляет API, который представляет любые документы HTML, XML или SVG и взаимодействует с ними. DOM — это модель документа, загруженная в браузер, и представляет документ в виде дерева узлов, где каждый node представляет часть документа (например, элемент, текст строка или комментарий).

## Классы

| Учебный класс | Описание |
| --- | --- |
| [Attr](./attr/) | Интерфейс Attr представляет атрибут в объекте Element. Обычно допустимые значения атрибута определяются в схеме, связанной с документом. |
| [CDATASection](./cdatasection/) | Разделы CDATA используются для экранирования блоков текста, содержащих символы, которые в противном случае считались бы разметкой. |
| [CharacterData](./characterdata/) | CharacterData расширяет Node набором атрибутов и методов для доступа к символьным данным в DOM. |
| [Comment](./comment/) | Наследуется от CharacterData и представляет содержимое комментария, т. е. все символы между начальным ' . |
| [Document](./document/) | Документ представляет собой весь документ HTML, XML или SVG. Концептуально это корень дерева документов и обеспечивает основной доступ к данным документа. |
| [DocumentFragment](./documentfragment/) | DocumentFragment — это «облегченный» или «минимальный» объект Document. Очень часто требуется извлечь часть дерева документа или создать новый фрагмент документа. |
| [DocumentType](./documenttype/) | DocumentType предоставляет интерфейс к списку сущностей, определенных для document |
| [DOMException](./domexception/) | Интерфейс DOMException представляет собой ненормальное событие (называемое исключением), которое возникает в результате вызова метода или доступа к свойству веб-API. В основном это то, как состояния ошибок описываются в веб-API. |
| [DOMObject](./domobject/) | Тип DOMObject используется для представления базового объекта для всей объектной модели документа. Для Java и ECMAScript тип DOMObject привязан к типу объекта. |
| [Element](./element/) | Интерфейс Element представляет элемент в документе HTML или XML. |
| [Entity](./entity/) | Представляет известную сущность, проанализированную или не проанализированную, в XML-документе. |
| [EntityReference](./entityreference/) | Узлы EntityReference могут использоваться для представления ссылки на объект в дереве. |
| [EventTarget](./eventtarget/) | [`EventTarget`](../aspose.html.dom/eventtarget/) интерфейс реализуется всеми узлами в реализации, которая поддерживает модель событий DOM. Таким образом, этот интерфейс можно получить, используя методы приведения для конкретных привязок к экземпляру интерфейса узла. Интерфейс позволяет регистрировать и удалять прослушиватели событий на ан[`EventTarget`](../aspose.html.dom/eventtarget/) и отправка событий на этот[`IEventTarget`](../aspose.html.dom.events/ieventtarget/) . |
| [Node](./node/) | Интерфейс узла является основным типом данных для всей объектной модели документа. Он представляет один узел в дереве документа. |
| [Notation](./notation/) | Представляет нотацию, объявленную в DTD. |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction представляет собой «инструкцию по обработке», используемую в XML как способ сохранения информации о процессоре в тексте документа. |
| [ShadowRoot](./shadowroot/) | ShadowRoot — корневой узел теневого дерева. |
| [Text](./text/) | Текстовый интерфейс наследуется от CharacterData и представляет текстовое содержимое (называемое символьными данными в XML) элемента или атрибута. |
| [TypeInfo](./typeinfo/) | TypeInfo представляет тип, на который ссылаются узлы Element или Attr, указанные в схемах, связанных с документом. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Контекст просмотра — это среда, в которой[`Document`](../aspose.html.dom/document/) объекты представлены пользователю. |
| [IChildNode](./ichildnode/) | определяет[`IChildNode`](../aspose.html.dom/ichildnode/) интерфейс, который должен быть реализован[`Node`](../aspose.html.dom/node/) у которого может быть родитель. |
| [IDocumentInit](./idocumentinit/) | Этот интерфейс обеспечивает[`Document`](../aspose.html.dom/document/) информация об инициализации. |
| [IDOMImplementation](./idomimplementation/) | Интерфейс DOMImplementation предоставляет ряд методов для выполнения операций, которые не зависят от какого-либо конкретного экземпляра объектной модели документа. |
| [IElementInit](./ielementinit/) | Этот интерфейс обеспечивает[`Element`](../aspose.html.dom/element/) информация об инициализации. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Представляет интерфейс, который должен наследоваться всеми элементами, для которых поддерживается обработка системных событий |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | определяет[`IChildNode`](../aspose.html.dom/ichildnode/) это не[`DOCUMENT_TYPE_NODE`](../aspose.html.dom/node/document_type_node/) . |
| [INonElementParentNode](./inonelementparentnode/) | определяет[`IParentNode`](../aspose.html.dom/iparentnode/) которые не относятся к типу Element. |
| [IParentNode](./iparentnode/) | Определяет[`IParentNode`](../aspose.html.dom/iparentnode/) интерфейс, который реализуется любыми возможными родителями. |
## перечисление

| перечисление | Описание |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Режимы, в которых может работать ShadowRoot. |


