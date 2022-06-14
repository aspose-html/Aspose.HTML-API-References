---
title: TimeEvent
second_title: Справочник по Aspose.HTML для .NET API
description: Интерфейс TimeEvent предоставляет конкретную контекстуальную информацию связанную с событиями Time. Возможны следующие типы событийbeginEvent endEvent и RepeatEvent.
type: docs
weight: 1450
url: /ru/net/aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

Интерфейс TimeEvent предоставляет конкретную контекстуальную информацию, связанную с событиями Time. Возможны следующие типы событий:beginEvent, endEvent и RepeatEvent.

```csharp
public class TimeEvent : Event
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Используется для указания того, является ли событие всплывающим. Если событие может всплыть, значение будет истинным, в противном случае значение будет ложным. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Используется для указания того, может ли событие предотвратить действие по умолчанию. Если действие по умолчанию можно предотвратить, значение равно true, в противном случае — значение false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Используется для указания объекта[`IEventTarget`](../../aspose.html.dom.events/ieventtarget)которого[`IEventListener`](../../aspose.html.dom.events/ieventlistener)в настоящее время обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Возвращает true, если функция preventDefault() была вызвана, когда значение отменяемого атрибута равно true, и false в противном случае. |
| [Detail](../../aspose.html.dom.svg.events/timeevent/detail) { get; } | Указывает некоторую подробную информацию о Событии, в зависимости от типа события. Для этого типа события указывает количество повторов анимации. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Используется для указания того, какая фаза потока событий оценивается в данный момент. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | Атрибут isTrusted должен возвращать значение, которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [Target](../../aspose.html.dom.events/event/target) { get; } | Используется для указания объекта[`IEventTarget`](../../aspose.html.dom.events/ieventtarget), которому изначально было отправлено событие. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp) { get; } | Используется для указания времени (в миллисекундах относительно эпохи), в которое было создано событие. Из-за того, что некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть доступно не для всех событий. Если недоступно, будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 года. |
| [Type](../../aspose.html.dom.events/event/type) { get; } | Имя события (без учета регистра). Имя должно быть именем XML. |
| [View](../../aspose.html.dom.svg.events/timeevent/view) { get; } | Атрибут представления идентифицирует AbstractView [DOM2VIEWS], из которого было сгенерировано событие. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Этот метод используется для получения объекта ECMAScriptType. |
| [InitEvent](../../aspose.html.dom.events/event/initevent)(string, bool, bool) | The[`InitEvent`](../../aspose.html.dom.events/event/initevent)метод используется для инициализации значения[`Event`](../../aspose.html.dom.events/event)созданного с помощью [`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent)интерфейс. |
| [InitTimeEvent](../../aspose.html.dom.svg.events/timeevent/inittimeevent)(string, IAbstractView, long) | Метод initTimeEvent используется для инициализации значения TimeEvent, созданного через интерфейс DocumentEvent. Этот метод может быть вызван только до того, как TimeEvent будет отправлен с помощью метода dispatchEvent, хотя при необходимости он может вызываться несколько раз на этом этапе. При многократном вызове последний вызов имеет приоритет. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault)() | Если событие можно отменить, метод[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault)используется для обозначения того, что событие должно быть отменено, что означает, что любое действие по умолчанию, обычно выполняемое реализацией в результате события, не произойдет. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation)() | Вызов этого метода не позволяет событию достичь любых прослушивателей событий, зарегистрированных после текущего, а при отправке в дерево также предотвращает достижение события любыми другими объектами. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation)() | Метод[`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation)используется для предотвращения дальнейшего распространения события во время потока событий. |

### Смотрите также

* class [Event](../../aspose.html.dom.events/event)
* пространство имен [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
