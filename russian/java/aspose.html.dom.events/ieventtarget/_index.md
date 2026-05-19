---
title: "Интерфейс IEventTarget"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.dom.events.IEventTarget. Интерфейс EventTarget реализуется всеми узлами (Node) в реализации, поддерживающей модель DOM Event. Поэтому этот интерфейс можно получить, используя методы приведения, специфичные для привязки, к экземпляру интерфейса Node. Интерфейс позволяет регистрировать и удалять Event Listeners и отправлять события к ним."
type: docs

url: /ru/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Интерфейс EventTarget реализуется всеми узлами в реализации, поддерживающей модель событий DOM. Поэтому этот интерфейс можно получить, используя методы приведения, специфичные для привязки, к экземпляру интерфейса Node. Интерфейс позволяет регистрировать и удалять слушатели событий и отправлять события им.

```java
public interface IEventTarget
```

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | Метод EventTarget addEventListener() задаёт функцию, которая будет вызвана каждый раз, когда указанное событие доставляется к цели. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | Метод EventTarget addEventListener() задаёт функцию, которая будет вызвана каждый раз, когда указанное событие доставляется к цели. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Отправляет событие (Event) к указанному EventTarget (синхронно), вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |

### См. также

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
