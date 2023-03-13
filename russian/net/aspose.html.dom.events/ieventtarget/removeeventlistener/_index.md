---
title: IEventTarget.RemoveEventListener
second_title: Справочник по Aspose.HTML для .NET API
description: IEventTarget метод. Этот метод позволяет удалить прослушиватели событий из цели события. ЕслиIEventListener удаляется изEventTarget пока он обрабатывает событие он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления.
type: docs
weight: 30
url: /ru/net/aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../ieventlistener/) удаляется из[`EventTarget`](../../../aspose.html.dom/eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Определяет тип события[`IEventListener`](../../ieventlistener/) удаляются. |
| listener | IEventListener | [`IEventListener`](../../ieventlistener/) параметр указывает[`IEventListener`](../../ieventlistener/) быть удалены. |

### Смотрите также

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* пространство имен [Aspose.Html.Dom.Events](../../ieventtarget/)
* сборка [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../ieventlistener/) удаляется из[`EventTarget`](../../../aspose.html.dom/eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Определяет тип события[`IEventListener`](../../ieventlistener/) удаляются. |
| listener | IEventListener | [`IEventListener`](../../ieventlistener/) параметр указывает[`IEventListener`](../../ieventlistener/) быть удалены. |
| useCapture | Boolean | Указывает, был ли удаленный EventListener зарегистрирован как прослушиватель захвата или нет. Если прослушиватель был зарегистрирован дважды, один с захватом и один без, каждый из них должен быть удален отдельно. того же слушателя и наоборот. |

### Смотрите также

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* пространство имен [Aspose.Html.Dom.Events](../../ieventtarget/)
* сборка [Aspose.HTML](../../../)


