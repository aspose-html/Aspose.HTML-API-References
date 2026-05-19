---
title: "Класс KeyboardEvent"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.events.KeyboardEvent. Интерфейс KeyboardEvent предоставляет специфическую контекстную информацию, связанную с клавиатурными устройствами. Каждое событие клавиатуры ссылается на клавишу с помощью значения. События клавиатуры обычно направляются к элементу, который имеет фокус."
type: docs

url: /ru/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

Интерфейс KeyboardEvent предоставляет специфическую контекстную информацию, связанную с клавиатурными устройствами. Каждое событие клавиатуры ссылается на клавишу с помощью значения. События клавиатуры обычно направляются к элементу, который имеет фокус.

```java
public class KeyboardEvent : UIEvent
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | Инициализирует новый экземпляр класса `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Свойства

| Имя | Описание |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true, если модификатор клавиши Alt (альтернативной) (или "Option") был активен. Неинициализированное значение этого атрибута ДОЛЖНО быть false. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе значение false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Используется для указания, может ли действие события быть отменено. Если действие может быть отменено, значение true, иначе значение false. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) Код содержит строку, идентифицирующую физическую нажимаемую клавишу. Значение не зависит от текущей раскладки клавиатуры или состояния модификаторов, поэтому конкретная клавиша всегда будет возвращать одно и то же значение. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true, если модификатор клавиши Control (контроль) был активен. Неинициализированное значение этого атрибута ДОЛЖНО быть false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Используется для указания [`IEventTarget`](../ieventtarget/), чьи [`IEventListener`](../ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, иначе возвращает false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Указывает некоторую детальную информацию о событии, в зависимости от типа события. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true, если событие клавиши происходит в рамках сессии композиции, то есть после события compositionstart и до соответствующего события compositionend. Неинициализированное значение этого атрибута ДОЛЖНО быть false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Атрибут isTrusted должен возвращать значение, с которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) Ключ содержит значение нажатой клавиши. Если значение имеет печатное представление, оно ДОЛЖНО быть непустой строкой Unicode‑символов, соответствующей алгоритму определения значения клавиши, определённому в этой спецификации. Если значение является управляющей клавишей без печатного представления, оно ДОЛЖНО быть одним из значений клавиш, определённых в наборе значений клавиш, согласно алгоритму определения значения клавиши. Реализации, которые не могут определить клавишу, ДОЛЖНЫ использовать значение клавиши Unidentified. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) Атрибут location содержит указание логического расположения клавиши на устройстве. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true, если модификатор клавиши meta (Meta) был активен. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true, если клавиша была нажата длительно. Удерживание клавиши ДОЛЖНО приводить к повторению событий keydown, beforeinput, input в указанном порядке, с частотой, определяемой конфигурацией системы. Для мобильных устройств с поведением длительного нажатия первый событие клавиши с атрибутом repeat, равным true, ДОЛЖНО служить индикатором длительного нажатия. Длительность, в течение которой клавиша ДОЛЖНА быть удержана, чтобы начать повторение, зависит от конфигурации. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true, если модификатор клавиши shift (Shift) был активен. |
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

## Поля

| Имя | Описание |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | Клавиша, активированная, происходит из левого расположения клавиши (когда для этой клавиши существует более одного возможного расположения). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | Активация клавиши происходила на цифровой клавиатуре или с помощью виртуальной клавиши, соответствующей цифровой клавиатуре (когда существует более одного возможного расположения этой клавиши). Обратите внимание, что клавиша NumLock всегда должна кодироваться с расположением DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | Активация клавиши происходила из правого расположения клавиши (когда существует более одного возможного расположения этой клавиши). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | Активацию клавиши НЕ ДОЛЖНО различать как левую или правую версию клавиши, и (за исключением клавиши NumLock) она не происходила с цифровой клавиатуры (или не происходила с виртуальной клавишей, соответствующей цифровой клавиатуре). |

### См. также

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
