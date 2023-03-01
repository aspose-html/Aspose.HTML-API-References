---
title: EventTarget.DispatchEvent
second_title: Справочник по Aspose.HTML для .NET API
description: EventTarget метод. Этот метод позволяет отправлять события в модель событий реализации.
type: docs
weight: 20
url: /ru/net/aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Этот метод позволяет отправлять события в модель событий реализации.

```csharp
public bool DispatchEvent(Event @event)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| event | Event | Задает тип события, поведение и контекстную информацию, которые будут использоваться при обработке события. |

### Возвращаемое значение

Возвращаемое значение`DispatchEvent` указывает, был ли какой-либо из слушателей, обработавших событие, вызванное[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) . Если[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) было вызвано, значение ложно, иначе значение истинно.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) |  |

### Примечания

События, отправленные таким образом, будут иметь такое же поведение при захвате и воспроизведении, что и события, отправленные непосредственно реализацией. Целью события является[`EventTarget`](../) на которой`DispatchEvent` называется .

### Смотрите также

* class [Event](../../../aspose.html.dom.events/event/)
* class [EventTarget](../)
* пространство имен [Aspose.Html.Dom](../../eventtarget/)
* сборка [Aspose.HTML](../../../)


