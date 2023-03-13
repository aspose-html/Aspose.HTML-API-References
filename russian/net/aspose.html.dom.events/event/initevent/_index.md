---
title: Event.InitEvent
second_title: Справочник по Aspose.HTML для .NET API
description: Event метод. InitEvent метод используется для инициализации значенияEvent создано через the IDocumentEvent интерфейс.
type: docs
weight: 110
url: /ru/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

`InitEvent` метод используется для инициализации значения[`Event`](../) создано через the [`IDocumentEvent`](../../idocumentevent/) интерфейс.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события. |
| bubbles | Boolean | если установлено`истинный` [пузыри]. |
| cancelable | Boolean | если установлено`истинный` [отменяемо]. |

### Примечания

Этот метод может быть вызван только до того, как событие будет отправлено через[`DispatchEvent`](../../ieventtarget/dispatchevent/) метод, , хотя при необходимости он может вызываться несколько раз в течение этой фазы. При многократном вызове последний вызов имеет приоритет. При вызове из подкласса интерфейса Event изменяются только значения, указанные в методе initEvent, все остальные атрибуты остаются без изменений.

### Смотрите также

* class [Event](../)
* пространство имен [Aspose.Html.Dom.Events](../../event/)
* сборка [Aspose.HTML](../../../)


