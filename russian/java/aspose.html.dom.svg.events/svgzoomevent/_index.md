---
title: "Класс SVGZoomEvent"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.svg.events.SVGZoomEvent. Событие масштабирования происходит, когда пользователь инициирует действие, которое приводит к изменению масштаба текущего представления фрагмента SVG‑документа. Обработчики событий распознаются только на элементах svg."
type: docs

url: /ru/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

Событие масштабирования происходит, когда пользователь инициирует действие, которое приводит к изменению масштаба текущего представления фрагмента SVG‑документа. Обработчики событий распознаются только на элементах ‘svg’.

```java
public class SVGZoomEvent : Event
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе значение false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Используется для указания, может ли действие события быть отменено. Если действие может быть отменено, значение true, иначе значение false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/currenttarget/) Используется для указания [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) чьи [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, иначе возвращает false. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Атрибут isTrusted должен возвращать значение, с которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) Коэффициент масштабирования, который будет установлен после обработки операции масштабирования. |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) Значения трансляции, которые будут установлены после обработки операции масштабирования. Объект SVGPoint доступен только для чтения. |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) Коэффициент масштабирования из предыдущих операций масштабирования, который был установлен до начала текущей операции. |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) Значения трансляции из предыдущих операций масштабирования, которые были установлены до начала текущей операции. Объект SVGPoint доступен только для чтения. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Используется для указания [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) к которому событие изначально было отправлено. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Используется для указания времени (в миллисекундах относительно эпохи), когда событие было создано. Поскольку некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для всех событий. Когда недоступно, будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 г. |
| [getType](../../com.aspose.html.dom.events/event/type/) Имя события (без учёта регистра). Имя должно быть XML‑именем. |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) Указанный прямоугольник масштабирования в единицах экрана. Объект SVGRect доступен только для чтения. |

## Методы

| Имя | Описание |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Метод [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) используется для инициализации значения [`Event`](../../com.aspose.html.dom.events/event/) созданного через интерфейс[`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Если событие отменяемо, метод [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) используется, чтобы указать, что событие должно быть отменено, то есть любое действие по умолчанию, обычно выполняемое реализацией в результате события, не произойдёт. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода предотвращает доставку события к любым обработчикам событий, зарегистрированным после текущего, и при распространении в дереве также предотвращает доставку события к другим объектам. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Метод [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) используется для предотвращения дальнейшего распространения события во время потока событий. |

### См. также

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
