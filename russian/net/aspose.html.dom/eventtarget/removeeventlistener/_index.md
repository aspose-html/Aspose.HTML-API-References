---
title: EventTarget.RemoveEventListener
second_title: Справочник по Aspose.HTML для .NET API
description: EventTarget метод. Этот метод позволяет удалить прослушиватели событий из цели события. ЕслиIEventListener удаляется изEventTarget пока он обрабатывает событие он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления.
type: docs
weight: 40
url: /ru/net/aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) удаляется из[`EventTarget`](../) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Определяет тип события[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) удаляются. |
| handler | DOMEventHandler | [`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) параметр указывает[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) быть удалены. |
| useCapture | Boolean | Указывает, был ли удаленный EventListener зарегистрирован как прослушиватель захвата или нет. Если прослушиватель был зарегистрирован дважды, один с захватом и один без, каждый из них должен быть удален отдельно. того же слушателя и наоборот. |

### Смотрите также

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* пространство имен [Aspose.Html.Dom](../../eventtarget/)
* сборка [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) удаляется из[`EventTarget`](../) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Определяет тип события[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) удаляются. |
| listener | IEventListener | [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) параметр указывает[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) быть удалены. |

### Смотрите также

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* пространство имен [Aspose.Html.Dom](../../eventtarget/)
* сборка [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) удаляется из[`EventTarget`](../) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Определяет тип события[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) удаляются. |
| listener | IEventListener | [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) параметр указывает[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) быть удалены. |
| useCapture | Boolean | Указывает, был ли удаленный EventListener зарегистрирован как прослушиватель захвата или нет. Если прослушиватель был зарегистрирован дважды, один с захватом и один без, каждый из них должен быть удален отдельно. того же слушателя и наоборот. |

### Смотрите также

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* пространство имен [Aspose.Html.Dom](../../eventtarget/)
* сборка [Aspose.HTML](../../../)


