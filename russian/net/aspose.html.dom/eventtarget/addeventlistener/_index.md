---
title: AddEventListener
second_title: Справочник по Aspose.HTML для .NET API
description: Этот метод позволяет регистрировать прослушиватели событий на цели события.
type: docs
weight: 10
url: /ru/net/aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(string, DOMEventHandler, bool) {#addeventlistener}

Этот метод позволяет регистрировать прослушиватели событий на цели события.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события, для которого регистрируется пользователь |
| handler | DOMEventHandler | Принимает[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler)для вызова при возникновении события. |
| useCapture | Boolean | Если true, useCapture указывает, что пользователь желает инициировать захват. После инициации захвата все события указанного типа будут отправлены в зарегистрированный [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) до того, как они будут отправлены на любые Цели Событий под ними в дереве. События, всплывающие вверх по дереву, не будут запускать[`IEventListener`](../../../aspose.html.dom.events/ieventlistener)предназначенный для использования захвата. |

### Примечания

Если[`IEventListener`](../../../aspose.html.dom.events/ieventlistener)добавляется в[`EventTarget`](../../eventtarget)пока он обрабатывает событие, он не будет запущен текущими действиями, но может быть запущен на более поздней стадии потока событий, например, на фазе всплытия.

Если на одномEventTargetс теми же параметрами дубликаты отбрасываются. Они не вызывают двойной вызов[`IEventListener`](../../../aspose.html.dom.events/ieventlistener), и поскольку они отбрасываются, их не нужно удалять с помощью [`RemoveEventListener`](../removeeventlistener) метод.

### Смотрите также

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler)
* class [EventTarget](../../eventtarget)
* пространство имен [Aspose.Html.Dom](../../eventtarget)
* сборка [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener) {#addeventlistener_1}

Этот метод позволяет регистрировать прослушиватели событий на цели события.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события, на которое регистрируется пользователь |
| listener | IEventListener | Принимает реализованный пользователем интерфейс, который содержит методы, вызываемые при возникновении события. |

### Примечания

Если[`IEventListener`](../../../aspose.html.dom.events/ieventlistener)добавляется в[`EventTarget`](../../eventtarget)пока он обрабатывает событие, он не будет запущен текущими действиями, но может быть запущен на более поздней стадии потока событий, например, на фазе всплытия.

Если на одномEventTargetс теми же параметрами дубликаты отбрасываются. Они не вызывают двойной вызов[`IEventListener`](../../../aspose.html.dom.events/ieventlistener), и поскольку они отбрасываются, их не нужно удалять с помощью [`RemoveEventListener`](../removeeventlistener) метод.

### Смотрите также

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* пространство имен [Aspose.Html.Dom](../../eventtarget)
* сборка [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_2}

Этот метод позволяет регистрировать прослушиватели событий на цели события.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события, на которое регистрируется пользователь |
| listener | IEventListener | Принимает реализованный пользователем интерфейс, который содержит методы, вызываемые при возникновении события. |
| useCapture | Boolean | Если true, useCapture указывает, что пользователь желает инициировать захват. После инициации захвата все события указанного типа будут отправлены в зарегистрированный [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) до того, как они будут отправлены на любые Цели Событий под ними в дереве. События, всплывающие вверх по дереву, не будут запускать[`IEventListener`](../../../aspose.html.dom.events/ieventlistener)предназначенный для использования захвата. |

### Примечания

Если[`IEventListener`](../../../aspose.html.dom.events/ieventlistener)добавляется в[`EventTarget`](../../eventtarget)пока он обрабатывает событие, он не будет запущен текущими действиями, но может быть запущен на более поздней стадии потока событий, например, на фазе всплытия.

Если на одномEventTargetс теми же параметрами дубликаты отбрасываются. Они не вызывают двойной вызов[`IEventListener`](../../../aspose.html.dom.events/ieventlistener), и поскольку они отбрасываются, их не нужно удалять с помощью [`RemoveEventListener`](../removeeventlistener) метод.

### Смотрите также

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* пространство имен [Aspose.Html.Dom](../../eventtarget)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
