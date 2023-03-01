---
title: Aspose.Html.Dom.Events
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Events namespace предоставляет объекты для любых событий связанных с обновлением DOM. Он включает в себя подписку на конкретную контекстную информацию  наблюдение  связанное с событием а также создание пользовательских событий.
type: docs
weight: 80
url: /ru/net/aspose.html.dom.events/
---
**Aspose.Html.Dom.Events** namespace предоставляет объекты для любых событий, связанных с обновлением DOM. Он включает в себя подписку на конкретную контекстную информацию , наблюдение , связанное с событием, а также создание пользовательских событий.

## Классы

| Учебный класс | Описание |
| --- | --- |
| [CustomEvent](./customevent/) | События, использующие интерфейс CustomEvent, могут использоваться для переноса пользовательских данных. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | [`DocumentLoadErrorEvent`](../aspose.html.dom.events/documentloaderrorevent/) возникает, когда запрошенный ресурс недоступен. |
| [DOMEventHandler](./domeventhandler/) | Представляет обратный вызов для обработки событий. |
| [ErrorEvent](./errorevent/) | [`ErrorEvent`](../aspose.html.dom.events/errorevent/) предоставляет контекстную информацию об ошибках, возникших во время выполнения. |
| [Event](./event/) | [`Event`](../aspose.html.dom.events/event/) используется для предоставления контекстной информации о событии обработчику, обрабатывающему событие. |
| [FocusEvent](./focusevent/) | Интерфейс FocusEvent предоставляет конкретную контекстную информацию, связанную с событиями Focus. |
| [InputEvent](./inputevent/) | События ввода отправляются в виде уведомлений при каждом обновлении DOM. |
| [KeyboardEvent](./keyboardevent/) | Интерфейс KeyboardEvent предоставляет конкретную контекстную информацию, связанную с клавиатурными устройствами. Каждое событие клавиатуры ссылается на клавишу, используя значение. События клавиатуры обычно направляются на элемент, находящийся в фокусе. |
| [MouseEvent](./mouseevent/) | Интерфейс MouseEvent предоставляет конкретную контекстную информацию, связанную с событиями мыши. |
| [UIEvent](./uievent/) | Интерфейс UIEvent предоставляет конкретную контекстную информацию, связанную с событиями пользовательского интерфейса. |
| [WheelEvent](./wheelevent/) | Интерфейс WheelEvent предоставляет конкретную контекстную информацию, связанную с событиями колеса. Чтобы создать экземпляр интерфейса WheelEvent, используйте конструктор WheelEvent, передав необязательный словарь WheelEventInit. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | [`IDocumentEvent`](../aspose.html.dom.events/idocumentevent/) Интерфейс предоставляет механизм, с помощью которого пользователь может создать[`Event`](../aspose.html.dom.events/event/) типа, поддерживаемого реализацией. |
| [IEventListener](./ieventlistener/) | [`IEventListener`](../aspose.html.dom.events/ieventlistener/)интерфейс является основным методом обработки событий. Пользователи реализуют[`IEventListener`](../aspose.html.dom.events/ieventlistener/) интерфейс и зарегистрировать своего слушателя на[`EventTarget`](../aspose.html.dom/eventtarget/) используя[`AddEventListener`](../aspose.html.dom/eventtarget/addeventlistener/) method. Пользователи также должны удалить свои[`IEventListener`](../aspose.html.dom.events/ieventlistener/) от его[`EventTarget`](../aspose.html.dom/eventtarget/) после того, как они завершили использование слушателя. |
| [IEventTarget](./ieventtarget/) | [`EventTarget`](../aspose.html.dom/eventtarget/) интерфейс реализуется всеми узлами в реализации, которая поддерживает модель событий DOM. Таким образом, этот интерфейс можно получить, используя методы приведения для конкретных привязок к экземпляру интерфейса узла. Интерфейс позволяет регистрировать и удалять прослушиватели событий на ан[`EventTarget`](../aspose.html.dom/eventtarget/) и отправка событий на этот[`IEventTarget`](../aspose.html.dom.events/ieventtarget/) . |


