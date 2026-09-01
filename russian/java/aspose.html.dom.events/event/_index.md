---
title: "Класс Event"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.events.Event class. Он используется для предоставления контекстной информации о событии обработчику, который обрабатывает событие"
type: docs

url: /ru/java/com.aspose.html.dom.events/event/
---
## Event class

Это используется для предоставления контекстной информации о событии обработчику, обрабатывающему событие.

```java
public class Event : DOMObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Event](event/#constructor)(String) | Инициализирует новый экземпляр класса `Event`. |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Свойства

| Имя | Описание |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе значение false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Используется для указания, может ли действие события быть предотвращено. Если действие может быть предотвращено, значение true, иначе значение false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Используется для указания [`IEventTarget`](../ieventtarget/), чьи [`IEventListener`](../ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, и false в противном случае. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Атрибут isTrusted должен возвращать значение, с которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Используется для указания [`IEventTarget`](../ieventtarget/), которому событие изначально было отправлено. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Используется для указания времени (в миллисекундах относительно эпохи), когда событие было создано. Поскольку некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для всех событий. Когда оно недоступно, возвращается значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 г. |
| [getType](../../com.aspose.html.dom.events/event/type/) Имя события (без учёта регистра). Имя должно быть XML‑именем. |

## Методы

| Имя | Описание |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Метод [`InitEvent`](./initevent/) используется для инициализации значения `Event`, созданного через интерфейс [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Если событие отменяемо, метод [`PreventDefault`](./preventdefault/) используется для указания, что событие должно быть отменено, что означает, что любое действие по умолчанию, обычно выполняемое реализацией в результате события, не произойдёт. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода препятствует доставке события к любым обработчикам событий, зарегистрированным после текущего, а при распространении в дереве также предотвращает доставку события к другим объектам. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Метод [`StopPropagation`](./stoppropagation/) используется для предотвращения дальнейшего распространения события во время потока событий. |

## Поля

| Имя | Описание |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | Текущая фаза события — фаза захвата. |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | Текущая фаза события — фаза всплытия. |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | Событие в данный момент оценивается у целевого объекта [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | События, которые в данный момент не отправляются, находятся в этой фазе. |

## Примечания

Объект, реализующий данный интерфейс, обычно передаётся в качестве первого параметра обработчику события. Более специфическая контекстная информация передаётся обработчикам событий путём наследования дополнительных интерфейсов, которые содержат сведения, непосредственно относящиеся к типу события, с которым они связаны. Эти производные интерфейсы также реализуются объектом, передаваемым слушателю события.

### См. также

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
