---
title: Class Event
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Events.Event сорт. Event используется для предоставления контекстной информации о событии обработчику обрабатывающему событие.
type: docs
weight: 770
url: /ru/net/aspose.html.dom.events/event/
---
## Event class

`Event` используется для предоставления контекстной информации о событии обработчику, обрабатывающему событие.

```csharp
public class Event : DOMObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Event](event/#constructor)(string) | Инициализирует новый экземпляр`Event` класс. |
| [Event](event/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Инициализирует новый экземпляр`Event` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Используется для указания того, является ли событие всплывающим событием. Если событие может всплывать, значение равно true, иначе значение false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Используется для указания того, можно ли предотвратить событие по умолчанию. Если действие по умолчанию можно предотвратить, значение равно true, в противном случае значение равно false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Используется для обозначения[`IEventTarget`](../ieventtarget/) чей[`IEventListener`](../ieventlistener/) в настоящее время обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Возвращает значение true, если функция preventDefault() была вызвана, когда значение отменяемого атрибута равно true, и значение false в противном случае. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Используется для указания того, какая фаза потока событий оценивается в данный момент. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Атрибут isTrusted должен возвращать значение, которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Используется для обозначения[`IEventTarget`](../ieventtarget/) которому изначально было отправлено событие. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Используется для указания времени (в миллисекундах относительно эпохи), в которое было создано событие. Из-за того, что некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для всех событий. Когда недоступно , будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 года. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Имя события (без учета регистра). Имя должно быть именем XML. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](./initevent/) метод используется для инициализации значения`Event` создано через the [`IDocumentEvent`](../idocumentevent/) интерфейс. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Если событие можно отменить,[`PreventDefault`](./preventdefault/) метод используется для обозначения того, что событие должно быть отменено, означает, что любое действие по умолчанию, обычно выполняемое реализацией в результате события, не произойдет. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода не позволяет событию достичь каких-либо прослушивателей событий, зарегистрированных после текущего, а при отправке в дерево также предотвращает достижение событием каких-либо других объектов. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](./stoppropagation/) используется метод предотвращения дальнейшего распространения события во время потока событий. |

## Поля

| Имя | Описание |
| --- | --- |
| const [AtTargetPhase](../../aspose.html.dom.events/event/attargetphase/) | Текущей фазой события является фаза захвата. |
| const [BubblingPhase](../../aspose.html.dom.events/event/bubblingphase/) | Текущей фазой события является фаза всплытия. |
| const [CapturingPhase](../../aspose.html.dom.events/event/capturingphase/) | Событие в настоящее время оценивается на цели[`IEventTarget`](../ieventtarget/) . |
| const [NonePhase](../../aspose.html.dom.events/event/nonephase/) | События, которые в настоящее время не отправляются, находятся в этой фазе. |

### Примечания

Объект, реализующий`Event` обычно передается в качестве первого параметра обработчику событий. Более конкретная контекстная информация передается обработчикам событий путем получения дополнительных интерфейсов от`Event` , которые содержат информацию, непосредственно относящуюся к типу события, которое они сопровождают. Эти производные интерфейсы также реализуются объектом, передаваемым прослушивателю событий.

### Смотрите также

* class [DOMObject](../../aspose.html.dom/domobject/)
* пространство имен [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* сборка [Aspose.HTML](../../)


