---
title: InitCustomEvent
second_title: Справочник по Aspose.HTML для .NET API
description: /// TheInitEventaspose.html.dom.events/event/initeventметод используется для инициализации значенияEventaspose.html.dom.events/eventсозданного с помощьюIDocumentEventaspose.html.dom.events/idocumenteventинтерфейс.
type: docs
weight: 30
url: /ru/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// The[`InitEvent`](../../event/initevent)метод используется для инициализации значения[`Event`](../../event)созданного с помощью[`IDocumentEvent`](../../idocumentevent)интерфейс.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события. |
| bubbles | Boolean | , если установлено значение` true` [пузыри]. |
| cancelable | Boolean | , если установлено значение` true` [cancelable]. |
| detail | Object | Пользовательские данные. |

### Примечания

Этот метод может быть вызван только до отправки события через[`DispatchEvent`](../../ieventtarget/dispatchevent)метод, хотя при необходимости он может вызываться несколько раз на этом этапе. При многократном вызове последний вызов имеет приоритет. При вызове из подкласса интерфейса Event изменяются только значения, указанные в методе initEvent, все остальные атрибуты остаются без изменений.

### Смотрите также

* class [CustomEvent](../../customevent)
* пространство имен [Aspose.Html.Dom.Events](../../customevent)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
