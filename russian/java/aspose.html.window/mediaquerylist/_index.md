---
title: "Класс MediaQueryList"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.window.MediaQueryList class. Объект MediaQueryList хранит информацию о медиазапросе, применённом к документу, с поддержкой как немедленного, так и событийного сопоставления с состоянием документа. См. спецификацию CSSOM View Module https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /ru/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

Объект MediaQueryList хранит информацию о медиазапросе, применённом к документу, с поддержкой как немедленного, так и событийного сопоставления с состоянием документа. См. спецификацию CSSOM View Module: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) Документ, связанный с объектом контекста. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) Булево значение, которое возвращает true, если документ в данный момент соответствует списку медиазапросов, или false в противном случае. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) Строка, представляющая сериализованный медиазапрос. |

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Метод addEventListener() интерфейса [`EventTarget `](../../com.aspose.html.dom/eventtarget/) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | Добавить обработчик события изменения состояния matches у MediaQueryList. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Отправляет событие указанному [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (синхронно), вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Выполняет определённые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | Удалить обработчик события изменения состояния matches у MediaQueryList. |

## События

| Имя | Описание |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | Событие, которое генерируется у MediaQueryList при изменении состояния matches. |

### См. также

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
