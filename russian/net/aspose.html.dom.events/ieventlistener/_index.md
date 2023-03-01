---
title: Interface IEventListener
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Events.IEventListener интерфейс. IEventListenerинтерфейс является основным методом обработки событий. Пользователи реализуютIEventListener интерфейс и зарегистрировать своего слушателя наEventTarget используяAddEventListener method. Пользователи также должны удалить своиIEventListener от егоEventTarget после того как они завершили использование слушателя.
type: docs
weight: 800
url: /ru/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

`IEventListener`интерфейс является основным методом обработки событий. Пользователи реализуют`IEventListener` интерфейс и зарегистрировать своего слушателя на[`EventTarget`](../../aspose.html.dom/eventtarget/) используя[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/) method. Пользователи также должны удалить свои`IEventListener` от его[`EventTarget`](../../aspose.html.dom/eventtarget/) после того, как они завершили использование слушателя.

```csharp
public interface IEventListener
```

## Методы

| Имя | Описание |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Этот метод вызывается всякий раз, когда происходит событие того типа, для которого`IEventListener` интерфейс был зарегистрирован. |

### Примечания

Когда узел копируется с помощью метода cloneNode, прослушиватели событий, прикрепленные к исходному узлу, не присоединяются к скопированному узлу. Если пользователь хочет, чтобы те же прослушиватели событий были добавлены во вновь созданную копию, пользователь должен добавить их вручную.

### Смотрите также

* пространство имен [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* сборка [Aspose.HTML](../../)


