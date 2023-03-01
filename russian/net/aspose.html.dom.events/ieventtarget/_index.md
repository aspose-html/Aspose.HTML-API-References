---
title: Interface IEventTarget
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Events.IEventTarget интерфейс. EventTarget интерфейс реализуется всеми узлами в реализации которая поддерживает модель событий DOM. Таким образом этот интерфейс можно получить используя методы приведения для конкретных привязок к экземпляру интерфейса узла. Интерфейс позволяет регистрировать и удалять прослушиватели событий на анEventTarget и отправка событий на этотIEventTarget .
type: docs
weight: 810
url: /ru/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

[`EventTarget`](../../aspose.html.dom/eventtarget/) интерфейс реализуется всеми узлами в реализации, которая поддерживает модель событий DOM. Таким образом, этот интерфейс можно получить, используя методы приведения для конкретных привязок к экземпляру интерфейса узла. Интерфейс позволяет регистрировать и удалять прослушиватели событий на ан[`EventTarget`](../../aspose.html.dom/eventtarget/) и отправка событий на этот`IEventTarget` .

```csharp
public interface IEventTarget
```

## Методы

| Имя | Описание |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | Этот метод позволяет регистрировать прослушиватели событий в цели события. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | Этот метод позволяет регистрировать прослушиватели событий в цели события. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Этот метод позволяет отправлять события в модель событий реализации. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../ieventlistener/) удаляется из[`EventTarget`](../../aspose.html.dom/eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../ieventlistener/) удаляется из[`EventTarget`](../../aspose.html.dom/eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |

### Смотрите также

* пространство имен [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* сборка [Aspose.HTML](../../)


