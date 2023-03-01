---
title: Class InputEvent
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Events.InputEvent сорт. События ввода отправляются в виде уведомлений при каждом обновлении DOM.
type: docs
weight: 820
url: /ru/net/aspose.html.dom.events/inputevent/
---
## InputEvent class

События ввода отправляются в виде уведомлений при каждом обновлении DOM.

```csharp
public class InputEvent : UIEvent
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [InputEvent](inputevent/#constructor)(string) | Инициализирует новый экземпляр`InputEvent` класс. |
| [InputEvent](inputevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Инициализирует новый экземпляр`InputEvent` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Используется для указания того, является ли событие всплывающим событием. Если событие может всплывать, значение равно true, иначе значение false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Используется для указания того, можно ли предотвратить событие по умолчанию. Если действие по умолчанию можно предотвратить, значение равно true, в противном случае значение равно false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Используется для обозначения[`IEventTarget`](../ieventtarget/) чей[`IEventListener`](../ieventlistener/) в настоящее время обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [Data](../../aspose.html.dom.events/inputevent/data/) { get; } | Данные содержат значение символов, сгенерированных методом ввода. Это МОЖЕТ быть одиночный символ Unicode или непустая последовательность символов Unicode [Unicode]. Символы СЛЕДУЕТ нормализовать, как определено формой нормализации Unicode NFC, определенной в [UAX15]. Этот атрибут МОЖЕТ содержать пустую строку. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Возвращает значение true, если функция preventDefault() была вызвана, когда значение отменяемого атрибута равно true, и значение false в противном случае. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Указывает некоторую подробную информацию о событии в зависимости от типа события. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Используется для указания того, какая фаза потока событий оценивается в данный момент. |
| [IsComposing](../../aspose.html.dom.events/inputevent/iscomposing/) { get; } | true, если входное событие происходит как часть сеанса композиции, т. е. после события «начало композиции» и перед соответствующим событием «конец композиции». Неинициализированное значение этого атрибута ДОЛЖНО быть ложным. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Атрибут isTrusted должен возвращать значение, которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Используется для обозначения[`IEventTarget`](../ieventtarget/) которому изначально было отправлено событие. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Используется для указания времени (в миллисекундах относительно эпохи), в которое было создано событие. Из-за того, что некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для всех событий. Когда недоступно , будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 года. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Имя события (без учета регистра). Имя должно быть именем XML. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | Атрибут представления идентифицирует окно, из которого было сгенерировано событие. Неинициализированное значение этого атрибута ДОЛЖНО быть нулевым. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](../event/initevent/) метод используется для инициализации значения[`Event`](../event/) создано через the [`IDocumentEvent`](../idocumentevent/) интерфейс. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Если событие можно отменить,[`PreventDefault`](../event/preventdefault/) метод используется для обозначения того, что событие должно быть отменено, означает, что любое действие по умолчанию, обычно выполняемое реализацией в результате события, не произойдет. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода не позволяет событию достичь каких-либо прослушивателей событий, зарегистрированных после текущего, а при отправке в дерево также предотвращает достижение событием каких-либо других объектов. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](../event/stoppropagation/) используется метод предотвращения дальнейшего распространения события во время потока событий. |

### Смотрите также

* class [UIEvent](../uievent/)
* пространство имен [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* сборка [Aspose.HTML](../../)


