---
title: "Класс InputEvent"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.events.InputEvent. События ввода отправляются в виде уведомлений каждый раз, когда DOM обновляется."
type: docs

url: /ru/java/com.aspose.html.dom.events/inputevent/
---
## InputEvent class

События ввода отправляются в виде уведомлений каждый раз, когда DOM обновляется.

```java
public class InputEvent : UIEvent
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [InputEvent](inputevent/#constructor)(String) | Инициализирует новый экземпляр класса `InputEvent`. |
| [InputEvent](inputevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Свойства

| Имя | Описание |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе значение false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Используется для указания, может ли действие события быть отменено. Если действие может быть отменено, значение true, иначе значение false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Используется для указания [`IEventTarget`](../ieventtarget/), чьи [`IEventListener`](../ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [getData](../../com.aspose.html.dom.events/inputevent/data/) Данные содержат значение символов, сгенерированных методом ввода. Это МОЖЕТ быть один отдельный символ Unicode или непустая последовательность символов Unicode [Unicode]. Символы ДОЛЖНЫ быть нормализованы в соответствии с формой нормализации Unicode NFC, определенной в [UAX15]. Этот атрибут МОЖЕТ содержать пустую строку. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, иначе возвращает false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Указывает некоторую детальную информацию о событии, в зависимости от типа события. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [getIsComposing](../../com.aspose.html.dom.events/inputevent/iscomposing/) true, если событие ввода происходит в рамках сессии композиции, т.е. после события compositionstart и до соответствующего события compositionend. Неинициализированное значение этого атрибута ДОЛЖНО быть false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Атрибут isTrusted должен возвращать значение, с которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Используется для указания [`IEventTarget`](../ieventtarget/) к которому событие изначально было отправлено. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Используется для указания времени (в миллисекундах относительно эпохи), когда событие было создано. Поскольку некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для всех событий. Когда недоступно, будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 г. |
| [getType](../../com.aspose.html.dom.events/event/type/) Имя события (без учёта регистра). Имя должно быть XML‑именем. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) Атрибут view идентифицирует окно (Window), из которого было сгенерировано событие. Неинициализированное значение этого атрибута ДОЛЖНО быть null. |

## Методы

| Имя | Описание |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](../event/initevent/) метод используется для инициализации значения [`Event`](../event/), созданного через интерфейс[`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Если событие отменяемо, метод [`PreventDefault`](../event/preventdefault/) используется для указания, что событие должно быть отменено, то есть любое действие по умолчанию, обычно выполняемое реализацией в результате события, не произойдёт. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода предотвращает доставку события к любым обработчикам событий, зарегистрированным после текущего, и при распространении в дереве также предотвращает доставку события к другим объектам. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Метод [`StopPropagation`](../event/stoppropagation/) используется для предотвращения дальнейшего распространения события во время потока событий. |

### См. также

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
