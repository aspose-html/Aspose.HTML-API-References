---
title: Event
second_title: Справочник по Aspose.HTML для .NET API
description: Event./eventиспользуется для предоставления контекстной информации о событии обработчику обрабатывающему событие .
type: docs
weight: 880
url: /ru/net/aspose.html.dom.events/event/
---
## Event class

[`Event`](../event)используется для предоставления контекстной информации о событии обработчику, обрабатывающему событие .

```csharp
public class Event : DOMObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Event](event#constructor)(string) | Инициализирует новый экземпляр класса[`Event`](../event). |
| [Event](event#constructor_1)(string, IDictionary&lt;string, object&gt;) | Инициализирует новый экземпляр класса[`Event`](../event). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Используется для указания того, является ли событие всплывающим. Если событие может всплыть, значение будет истинным, в противном случае значение будет ложным. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Используется для указания того, может ли событие предотвратить действие по умолчанию. Если действие по умолчанию можно предотвратить, значение равно true, в противном случае — значение false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Используется для указания объекта[`IEventTarget`](../ieventtarget)которого[`IEventListener`](../ieventlistener)в настоящее время обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Возвращает true, если функция preventDefault() была вызвана, когда значение отменяемого атрибута равно true, и false в противном случае. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Используется для указания того, какая фаза потока событий оценивается в данный момент. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | Атрибут isTrusted должен возвращать значение, которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [Target](../../aspose.html.dom.events/event/target) { get; } | Используется для указания объекта[`IEventTarget`](../ieventtarget), которому изначально было отправлено событие. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp) { get; } | Используется для указания времени (в миллисекундах относительно эпохи), в которое было создано событие. Из-за того, что некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть доступно не для всех событий. Если недоступно, будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 года. |
| [Type](../../aspose.html.dom.events/event/type) { get; } | Имя события (без учета регистра). Имя должно быть именем XML. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Этот метод используется для получения объекта ECMAScriptType. |
| [InitEvent](../../aspose.html.dom.events/event/initevent)(string, bool, bool) | The[`InitEvent`](./initevent)метод используется для инициализации значения[`Event`](../event)созданного с помощью [`IDocumentEvent`](../idocumentevent)интерфейс. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault)() | Если событие можно отменить, метод[`PreventDefault`](./preventdefault)используется для обозначения того, что событие должно быть отменено, что означает, что любое действие по умолчанию, обычно выполняемое реализацией в результате события, не произойдет. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation)() | Вызов этого метода не позволяет событию достичь любых прослушивателей событий, зарегистрированных после текущего, а при отправке в дерево также предотвращает достижение события любыми другими объектами. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation)() | Метод[`StopPropagation`](./stoppropagation)используется для предотвращения дальнейшего распространения события во время потока событий. |

## Поля

| Имя | Описание |
| --- | --- |
| const [AtTargetPhase](../../aspose.html.dom.events/event/attargetphase) | Текущей фазой события является фаза захвата. |
| const [BubblingPhase](../../aspose.html.dom.events/event/bubblingphase) | Текущей фазой события является фаза всплытия. |
| const [CapturingPhase](../../aspose.html.dom.events/event/capturingphase) | Событие в настоящее время оценивается в целевом объекте[`IEventTarget`](../ieventtarget). |
| const [NonePhase](../../aspose.html.dom.events/event/nonephase) | В этой фазе находятся события, которые в настоящее время не отправляются. |

### Примечания

Объект, реализующий[`Event`](../event)обычно передается в качестве первого параметра обработчику событий. Более конкретная контекстная информация передается обработчикам событий путем получения дополнительных интерфейсов от[`Event`](../event) , которые содержат информацию непосредственно связанные с типом события, которое они сопровождают. Эти производные интерфейсы также реализуются объектом, переданным прослушивателю событий.

### Смотрите также

* class [DOMObject](../../aspose.html.dom/domobject)
* пространство имен [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
