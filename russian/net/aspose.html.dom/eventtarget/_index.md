---
title: Class EventTarget
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.EventTarget сорт. EventTarget интерфейс реализуется всеми узлами в реализации которая поддерживает модель событий DOM. Таким образом этот интерфейс можно получить используя методы приведения для конкретных привязок к экземпляру интерфейса узла. Интерфейс позволяет регистрировать и удалять прослушиватели событий на анEventTarget и отправка событий на этотIEventTarget .
type: docs
weight: 720
url: /ru/net/aspose.html.dom/eventtarget/
---
## EventTarget class

`EventTarget` интерфейс реализуется всеми узлами в реализации, которая поддерживает модель событий DOM. Таким образом, этот интерфейс можно получить, используя методы приведения для конкретных привязок к экземпляру интерфейса узла. Интерфейс позволяет регистрировать и удалять прослушиватели событий на ан`EventTarget` и отправка событий на этот[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) .

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Методы

| Имя | Описание |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener) | Этот метод позволяет регистрировать прослушиватели событий в цели события. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(string, DOMEventHandler, bool) | Этот метод позволяет регистрировать прослушиватели событий в цели события. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(string, IEventListener, bool) | Этот метод позволяет регистрировать прослушиватели событий в цели события. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Этот метод позволяет отправлять события в модель событий реализации. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Выполняет определяемые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) удаляется из`EventTarget` пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(string, DOMEventHandler, bool) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) удаляется из`EventTarget` пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(string, IEventListener, bool) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) удаляется из`EventTarget` пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |

### Смотрите также

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* пространство имен [Aspose.Html.Dom](../../aspose.html.dom/)
* сборка [Aspose.HTML](../../)


