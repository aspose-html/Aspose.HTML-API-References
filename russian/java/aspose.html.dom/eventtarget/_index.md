---
title: "Класс EventTarget"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.EventTarget. Интерфейс EventTarget реализуется объектами, которые могут получать события и могут иметь слушатели для них. Другими словами, любой получатель событий реализует три метода, связанные с этим интерфейсом."
type: docs

url: /ru/java/com.aspose.html.dom/eventtarget/
---
## EventTarget class

Интерфейс EventTarget реализуется объектами, которые могут получать события и могут иметь слушатели для них. Другими словами, любой получатель событий реализует три метода, связанные с этим интерфейсом.

[`Element`](../element/), and its children, as well as [`Document`](../document/) and Window, are the most common event targets, but other objects can be event targets, too.

```java
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EventTarget](eventtarget/)() | Инициализирует новый экземпляр объекта EventTarget. |

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener) | Метод addEventListener() интерфейса `EventTarget `настраивает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется получателю. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(String, DOMEventHandler, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(String, IEventListener, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Отправляет событие указанному [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (синхронно), вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Выполняет определённые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(String, DOMEventHandler, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(String, IEventListener, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |

### См. также

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
