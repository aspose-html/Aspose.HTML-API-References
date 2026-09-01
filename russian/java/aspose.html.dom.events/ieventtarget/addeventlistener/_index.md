---
title: "IEventTarget.AddEventListener"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод IEventTarget. Метод EventTarget addEventListener устанавливает функцию, которая будет вызываться каждый раз, когда указанный событие доставляется целевому объекту."
type: docs

url: /ru/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

Метод EventTarget addEventListener() задаёт функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели.

Общие целевые объекты — Element, Document и Window, но целевым может быть любой объект, поддерживающий события (например, XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | String | Чувствительная к регистру строка (String), представляющая тип события, на которое следует слушать. |
| слушатель | IEventListener | Принимает интерфейс, реализованный пользователем, который содержит методы, вызываемые при возникновении события. |

## Примечания

Если  добавлен к  во время обработки события, он не будет сработан текущими действиями, но может быть сработан на более поздней стадии потока событий, такой как фаза всплытия. Если несколько одинаковых Event Listeners зарегистрированы на одном объекте с одинаковыми параметрами, дублирующие экземпляры отбрасываются. Они не вызывают  дважды, и поскольку они отбрасываются, их не нужно удалять с помощью метода .

### См. также

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

Метод EventTarget addEventListener() задаёт функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели.

Общие целевые объекты — Element, Document и Window, но целевым может быть любой объект, поддерживающий события (например, XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | String | Чувствительная к регистру строка (String), представляющая тип события, на которое следует слушать. |
| слушатель | IEventListener | Принимает интерфейс, реализованный пользователем, который содержит методы, вызываемые при возникновении события. |
| useCapture | Boolean | Если true, useCapture указывает, что пользователь хочет инициировать захват. После инициации захвата все события указанного типа будут отправлены зарегистрированным  перед тем, как они будут отправлены любым Event Targets ниже их в дереве. События, всплывающие вверх по дереву, не вызовут назначенный  использовать захват. |

## Примечания

Если  добавлен к  во время обработки события, он не будет сработан текущими действиями, но может быть сработан на более поздней стадии потока событий, такой как фаза всплытия. Если несколько одинаковых Event Listeners зарегистрированы на одном объекте с одинаковыми параметрами, дублирующие экземпляры отбрасываются. Они не вызывают  дважды, и поскольку они отбрасываются, их не нужно удалять с помощью метода .

### См. также

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
