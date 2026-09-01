---
title: "EventTarget.RemoveEventListener"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод EventTarget. Этот метод позволяет удалять обработчики событий из целевого объекта. Если обработчик удалён во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после удаления."
type: docs

url: /ru/java/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления.

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | String | Указывает тип события удаляемого. |
| обработчик | DOMEventHandler | Параметр указывает, что будет удалено. |
| useCapture | Boolean | Указывает, был ли удаляемый EventListener зарегистрирован как захватывающий слушатель или нет. Если слушатель был зарегистрирован дважды, один с захватом и один без, каждый должен быть удалён отдельно. Удаление захватывающего слушателя не влияет на неконтролируемую версию того же слушателя и наоборот. |

### См. также

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | String | Указывает тип события удаляемого. |
| слушатель | IEventListener | Параметр указывает, что будет удалено. |

### См. также

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | String | Указывает тип события удаляемого. |
| слушатель | IEventListener | Параметр указывает, что будет удалено. |
| useCapture | Boolean | Указывает, был ли удаляемый EventListener зарегистрирован как захватывающий слушатель или нет. Если слушатель был зарегистрирован дважды, один с захватом и один без, каждый должен быть удалён отдельно. Удаление захватывающего слушателя не влияет на неконтролируемую версию того же слушателя и наоборот. |

### См. также

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
