---
title: IEventTarget.AddEventListener
second_title: Справочник по Aspose.HTML для .NET API
description: IEventTarget метод. Этот метод позволяет регистрировать прослушиватели событий в цели события.
type: docs
weight: 10
url: /ru/net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

Этот метод позволяет регистрировать прослушиватели событий в цели события.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события, на которое регистрируется пользователь |
| listener | IEventListener | Принимает реализованный пользователем интерфейс, который содержит методы, вызываемые при возникновении события. |

### Примечания

Если[`IEventListener`](../../ieventlistener/) добавляется к[`EventTarget`](../../../aspose.html.dom/eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями, но может быть запущен на более позднем этапе потока событий, например, на этапе всплытия.

Если несколько идентичных прослушивателей событий зарегистрированы на одном[`EventTarget`](../../../aspose.html.dom/eventtarget/)с теми же параметрами повторяющиеся экземпляры отбрасываются. Они не вызывают[`IEventListener`](../../ieventlistener/) вызываться дважды, и поскольку они отбрасываются, их не нужно удалять с помощью the [`RemoveEventListener`](../removeeventlistener/) метод.

### Смотрите также

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* пространство имен [Aspose.Html.Dom.Events](../../ieventtarget/)
* сборка [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

Этот метод позволяет регистрировать прослушиватели событий в цели события.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события, на которое регистрируется пользователь |
| listener | IEventListener | Принимает реализованный пользователем интерфейс, который содержит методы, вызываемые при возникновении события. |
| useCapture | Boolean | Если значение true, useCapture указывает, что пользователь хочет инициировать захват.[`IEventListener`](../../ieventlistener/) до того, как они будут отправлены на любые цели событий, находящиеся под ними в дереве. События, которые всплывают вверх по дереву, не вызовут[`IEventListener`](../../ieventlistener/) предназначены для использования захвата. |

### Примечания

Если[`IEventListener`](../../ieventlistener/) добавляется к[`EventTarget`](../../../aspose.html.dom/eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями, но может быть запущен на более позднем этапе потока событий, например, на этапе всплытия.

Если несколько идентичных прослушивателей событий зарегистрированы на одном[`EventTarget`](../../../aspose.html.dom/eventtarget/)с теми же параметрами повторяющиеся экземпляры отбрасываются. Они не вызывают[`IEventListener`](../../ieventlistener/) вызываться дважды, и поскольку они отбрасываются, их не нужно удалять с помощью the [`RemoveEventListener`](../removeeventlistener/) метод.

### Смотрите также

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* пространство имен [Aspose.Html.Dom.Events](../../ieventtarget/)
* сборка [Aspose.HTML](../../../)


