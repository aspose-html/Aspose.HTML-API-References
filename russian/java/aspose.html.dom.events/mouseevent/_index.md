---
title: "Класс MouseEvent"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.events.MouseEvent. Интерфейс MouseEvent предоставляет специфическую контекстную информацию, связанную с событиями мыши."
type: docs

url: /ru/java/com.aspose.html.dom.events/mouseevent/
---
## MouseEvent class

Интерфейс MouseEvent предоставляет специфическую контекстную информацию, связанную с событиями мыши.

```java
public class MouseEvent : UIEvent
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MouseEvent](mouseevent/#constructor)(String) | Инициализирует новый экземпляр класса `MouseEvent`. |
| [MouseEvent](mouseevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Свойства

| Имя | Описание |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) Смотрите атрибут altKey. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе значение false. |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) Во время событий мыши, вызванных нажатием или отпусканием кнопки мыши, атрибут button ДОЛЖЕН использоваться для указания, какая кнопка указательного устройства сменила состояние. |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) При любых событиях мыши атрибут buttons ДОЛЖЕН использоваться для указания, какая комбинация кнопок мыши в данный момент нажата, выраженная в виде битовой маски. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Используется для указания, может ли действие события быть отменено. Если действие может быть отменено, значение true, иначе значение false. |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) Горизонтальная координата, в которой событие произошло относительно области просмотра, связанной с событием. |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) Вертикальная координата, в которой событие произошло относительно области просмотра, связанной с событием. |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) Смотрите атрибут ctrlKey. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Используется для указания [`IEventTarget`](../ieventtarget/), чьи [`IEventListener`](../ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, иначе возвращает false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Указывает некоторую детальную информацию о событии, в зависимости от типа события. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Атрибут isTrusted должен возвращать значение, с которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) Смотрите атрибут metaKey. |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) Используется для идентификации вторичного EventTarget, связанного с UI‑событием, в зависимости от типа события. |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) Горизонтальная координата, в которой произошло событие, относительно начала системы координат экрана. |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) Вертикальная координата, в которой произошло событие, относительно начала системы координат экрана. |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) См. атрибут shiftKey. |
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
