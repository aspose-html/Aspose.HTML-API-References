---
title: Class TimeEvent
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Svg.Events.TimeEvent сорт. Интерфейс TimeEvent предоставляет конкретную контекстную информацию связанную с событиями Time. Возможны следующие типы событий beginEvent endEvent и RepeatEvent.
type: docs
weight: 1340
url: /ru/net/aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

Интерфейс TimeEvent предоставляет конкретную контекстную информацию, связанную с событиями Time. Возможны следующие типы событий: beginEvent, endEvent и RepeatEvent.

```csharp
public class TimeEvent : Event
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Используется для указания того, является ли событие всплывающим событием. Если событие может всплывать, значение равно true, иначе значение false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Используется для указания того, можно ли предотвратить событие по умолчанию. Если действие по умолчанию можно предотвратить, значение равно true, в противном случае значение равно false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Используется для обозначения[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) чей[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) в настоящее время обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Возвращает значение true, если функция preventDefault() была вызвана, когда значение отменяемого атрибута равно true, и значение false в противном случае. |
| [Detail](../../aspose.html.dom.svg.events/timeevent/detail/) { get; } | Указывает некоторую подробную информацию о событии в зависимости от типа события. Для этого типа события указывает номер повтора анимации. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Используется для указания того, какая фаза потока событий оценивается в данный момент. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Атрибут isTrusted должен возвращать значение, которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Используется для обозначения[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) которому изначально было отправлено событие. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Используется для указания времени (в миллисекундах относительно эпохи), в которое было создано событие. Из-за того, что некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для всех событий. Когда недоступно , будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 года. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Имя события (без учета регистра). Имя должно быть именем XML. |
| [View](../../aspose.html.dom.svg.events/timeevent/view/) { get; } | Атрибут представления идентифицирует AbstractView [DOM2VIEWS], из которого было сгенерировано событие. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](../../aspose.html.dom.events/event/initevent/) метод используется для инициализации значения[`Event`](../../aspose.html.dom.events/event/) создано через the [`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/) интерфейс. |
| [InitTimeEvent](../../aspose.html.dom.svg.events/timeevent/inittimeevent/)(string, IAbstractView, long) | Метод initTimeEvent используется для инициализации значения TimeEvent, созданного через интерфейс DocumentEvent. Этот метод может быть вызван только до того, как TimeEvent будет отправлен с помощью метода dispatchEvent, хотя при необходимости он может вызываться несколько раз на этом этапе. При многократном вызове последний вызов имеет приоритет. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Если событие можно отменить,[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/) метод используется для обозначения того, что событие должно быть отменено, означает, что любое действие по умолчанию, обычно выполняемое реализацией в результате события, не произойдет. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода не позволяет событию достичь каких-либо прослушивателей событий, зарегистрированных после текущего, а при отправке в дерево также предотвращает достижение событием каких-либо других объектов. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/) используется метод предотвращения дальнейшего распространения события во время потока событий. |

### Смотрите также

* class [Event](../../aspose.html.dom.events/event/)
* пространство имен [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* сборка [Aspose.HTML](../../)


