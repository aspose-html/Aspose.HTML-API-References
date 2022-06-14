---
title: ErrorEvent
second_title: Справочник по Aspose.HTML для .NET API
description: ErrorEvent./erroreventпредоставляет контекстную информацию об ошибках возникших во время выполнения.
type: docs
weight: 870
url: /ru/net/aspose.html.dom.events/errorevent/
---
## ErrorEvent class

[`ErrorEvent`](../errorevent)предоставляет контекстную информацию об ошибках, возникших во время выполнения.

```csharp
public class ErrorEvent : Event
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ErrorEvent](errorevent#constructor_1)(Exception) | Инициализирует новый экземпляр класса[`ErrorEvent`](../errorevent). |
| [ErrorEvent](errorevent#constructor)(IDictionary&lt;string, object&gt;) | Инициализирует новый экземпляр класса[`ErrorEvent`](../errorevent). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Используется для указания того, является ли событие всплывающим. Если событие может всплыть, значение будет истинным, в противном случае значение будет ложным. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Используется для указания того, может ли событие предотвратить действие по умолчанию. Если действие по умолчанию можно предотвратить, значение равно true, в противном случае — значение false. |
| [ColNo](../../aspose.html.dom.events/errorevent/colno) { get; } | Атрибут colno должен возвращать значение, которым он был инициализирован. При создании объекта этот атрибут должен быть инициализирован нулем. Он представляет собой номер столбца, в котором произошла ошибка в скрипте. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Используется для указания объекта[`IEventTarget`](../ieventtarget)которого[`IEventListener`](../ieventlistener)в настоящее время обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Возвращает true, если функция preventDefault() была вызвана, когда значение отменяемого атрибута равно true, и false в противном случае. |
| [Error](../../aspose.html.dom.events/errorevent/error) { get; } | Атрибут ошибки должен возвращать значение, которым он был инициализирован. При создании объекта этот атрибут должен быть инициализирован нулем. Там, где это уместно, устанавливается объект, представляющий ошибку (например, объект исключения в случае неперехваченного исключения DOM). |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Используется для указания того, какая фаза потока событий оценивается в данный момент. |
| [FileName](../../aspose.html.dom.events/errorevent/filename) { get; } | Атрибут имени файла должен возвращать значение, которым он был инициализирован. При создании объекта этот атрибут должен быть инициализирован пустой строкой. Он представляет собой абсолютный URL-адрес сценария, в котором изначально возникла ошибка. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | Атрибут isTrusted должен возвращать значение, которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [LineNo](../../aspose.html.dom.events/errorevent/lineno) { get; } | Атрибут lineno должен возвращать значение, которым он был инициализирован. При создании объекта этот атрибут должен быть инициализирован нулем. Он представляет собой номер строки, в которой произошла ошибка в скрипте. |
| [Message](../../aspose.html.dom.events/errorevent/message) { get; } | Атрибут сообщения должен возвращать значение, которым он был инициализирован. При создании объекта этот атрибут должен быть инициализирован пустой строкой. Он представляет собой сообщение об ошибке. |
| [Target](../../aspose.html.dom.events/event/target) { get; } | Используется для указания объекта[`IEventTarget`](../ieventtarget), которому изначально было отправлено событие. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp) { get; } | Используется для указания времени (в миллисекундах относительно эпохи), в которое было создано событие. Из-за того, что некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть доступно не для всех событий. Если недоступно, будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 года. |
| [Type](../../aspose.html.dom.events/event/type) { get; } | Имя события (без учета регистра). Имя должно быть именем XML. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Этот метод используется для получения объекта ECMAScriptType. |
| [InitEvent](../../aspose.html.dom.events/event/initevent)(string, bool, bool) | The[`InitEvent`](../event/initevent)метод используется для инициализации значения[`Event`](../event)созданного с помощью [`IDocumentEvent`](../idocumentevent)интерфейс. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault)() | Если событие можно отменить, метод[`PreventDefault`](../event/preventdefault)используется для обозначения того, что событие должно быть отменено, что означает, что любое действие по умолчанию, обычно выполняемое реализацией в результате события, не произойдет. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation)() | Вызов этого метода не позволяет событию достичь любых прослушивателей событий, зарегистрированных после текущего, а при отправке в дерево также предотвращает достижение события любыми другими объектами. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation)() | Метод[`StopPropagation`](../event/stoppropagation)используется для предотвращения дальнейшего распространения события во время потока событий. |

### Смотрите также

* class [Event](../event)
* пространство имен [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
