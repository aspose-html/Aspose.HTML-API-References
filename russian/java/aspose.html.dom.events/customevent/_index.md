---
title: "CustomEvent Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.events.CustomEvent класс. События, использующие интерфейс CustomEvent, могут использоваться для передачи пользовательских данных."
type: docs

url: /ru/java/com.aspose.html.dom.events/customevent/
---
## CustomEvent class

События, использующие интерфейс CustomEvent, могут использоваться для передачи пользовательских данных.

```java
public class CustomEvent : Event
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CustomEvent](customevent/#constructor)(String) | Инициализирует новый экземпляр класса `CustomEvent`. |
| [CustomEvent](customevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Свойства

| Имя | Описание |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе значение false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Используется для указания, может ли действие события быть предотвращено. Если действие может быть предотвращено, значение true, иначе значение false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Используется для указания [`IEventTarget`](../ieventtarget/), чьи [`IEventListener`](../ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, и false в противном случае. |
| [getDetail](../../com.aspose.html.dom.events/customevent/detail/) Получает пользовательские данные. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Атрибут isTrusted должен возвращать значение, с которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Используется для указания [`IEventTarget`](../ieventtarget/), которому событие изначально было отправлено. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Используется для указания времени (в миллисекундах относительно эпохи), когда событие было создано. Поскольку некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для всех событий. Когда оно недоступно, возвращается значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 г. |
| [getType](../../com.aspose.html.dom.events/event/type/) Имя события (без учёта регистра). Имя должно быть XML‑именем. |

## Методы

| Имя | Описание |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [initCustomEvent](../../com.aspose.html.dom.events/customevent/initcustomevent/)(String, bool, bool, object) | /// Метод [`InitEvent`](../event/initevent/) используется для инициализации значения [`Event`](../event/), созданного через интерфейс [`IDocumentEvent`](../idocumentevent/). |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Метод [`InitEvent`](../event/initevent/) используется для инициализации значения [`Event`](../event/), созданного через интерфейс [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Если событие отменяемо, метод [`PreventDefault`](../event/preventdefault/) используется для указания, что событие должно быть отменено, то есть любое действие по умолчанию, обычно выполняемое реализацией в результате события, не будет выполнено. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода препятствует доставке события к любым обработчикам событий, зарегистрированным после текущего, а при распространении в дереве также предотвращает доставку события к другим объектам. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Метод [`StopPropagation`](../event/stoppropagation/) используется для предотвращения дальнейшего распространения события во время потока событий. |

### См. также

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
