---
title: CustomEvent.InitCustomEvent
second_title: Справочник по Aspose.HTML для .NET API
description: CustomEvent метод. ///InitEvent метод используется для инициализации значенияEvent созданный с помощьюIDocumentEvent интерфейс.
type: docs
weight: 30
url: /ru/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

///[`InitEvent`](../../event/initevent/) метод используется для инициализации значения[`Event`](../../event/) созданный с помощью[`IDocumentEvent`](../../idocumentevent/) интерфейс.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события. |
| bubbles | Boolean | если установлено`истинный` [пузыри]. |
| cancelable | Boolean | если установлено`истинный` [отменяемо]. |
| detail | Object | Пользовательские данные. |

### Примечания

Этот метод может быть вызван только до того, как событие будет отправлено через[`DispatchEvent`](../../ieventtarget/dispatchevent/) метод, , хотя при необходимости он может вызываться несколько раз в течение этой фазы. При многократном вызове последний вызов имеет приоритет. При вызове из подкласса интерфейса Event изменяются только значения, указанные в методе initEvent, все остальные атрибуты остаются без изменений.

### Смотрите также

* class [CustomEvent](../)
* пространство имен [Aspose.Html.Dom.Events](../../customevent/)
* сборка [Aspose.HTML](../../../)


