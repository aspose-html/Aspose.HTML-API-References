---
title: "Класс TimeEvent"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.svg.events.TimeEvent. Интерфейс TimeEvent предоставляет специфическую контекстную информацию, связанную со событиями времени. Различные типы событий, которые могут возникать, — beginEvent, endEvent и repeatEvent."
type: docs

url: /ru/java/com.aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

Интерфейс TimeEvent предоставляет конкретную контекстную информацию, связанную со временными событиями. Различные типы событий, которые могут возникать, включают: beginEvent, endEvent и repeatEvent.

```java
public class TimeEvent : Event
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе значение false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Используется для указания, может ли действие события быть предотвращено. Если действие может быть предотвращено, значение true, иначе значение false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Используется для указания [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/), чьи [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, и false в противном случае. |
| [getDetail](../../com.aspose.html.dom.svg.events/timeevent/detail/) Указывает некоторую детальную информацию о событии, в зависимости от типа события. Для этого типа события указывает номер повторения анимации. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Атрибут isTrusted должен возвращать значение, с которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Используется для указания [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/), которому изначально было отправлено событие. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Используется для указания времени (в миллисекундах относительно эпохи), когда событие было создано. Поскольку некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для всех событий. Когда оно недоступно, возвращается значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 г. |
| [getType](../../com.aspose.html.dom.events/event/type/) Имя события (без учёта регистра). Имя должно быть XML‑именем. |
| [getView](../../com.aspose.html.dom.svg.events/timeevent/view/) Атрибут view определяет AbstractView [DOM2VIEWS], из которого было сгенерировано событие. |

## Методы

| Имя | Описание |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Метод [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) используется для инициализации значения [`Event`](../../com.aspose.html.dom.events/event/), созданного через интерфейс[`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/). |
| [initTimeEvent](../../com.aspose.html.dom.svg.events/timeevent/inittimeevent/)(String, IAbstractView, long) | Метод initTimeEvent используется для инициализации значения TimeEvent, созданного через интерфейс DocumentEvent. Этот метод может быть вызван только до того, как TimeEvent будет отправлен с помощью метода dispatchEvent, хотя при необходимости его можно вызвать несколько раз в этом этапе. Если вызвано несколько раз, приоритет имеет последнее вызов. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Если событие отменяемо, метод [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) используется для указания, что событие должно быть отменено, то есть любое действие по умолчанию, обычно выполняемое реализацией в результате события, не будет выполнено. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода препятствует доставке события к любым обработчикам событий, зарегистрированным после текущего, а при распространении в дереве также предотвращает доставку события к другим объектам. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Метод [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) используется для предотвращения дальнейшего распространения события во время потока событий. |

### См. также

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
