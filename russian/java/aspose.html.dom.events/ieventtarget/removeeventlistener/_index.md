---
title: "IEventTarget.RemoveEventListener"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод IEventTarget. Этот метод позволяет удалять Event Listeners из цели события. Если Event Listener удаляется из цели во время обработки события, он не будет вызван текущими действиями. Event Listeners никогда не могут быть вызваны после удаления"
type: docs

url: /ru/java/com.aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(String, IEventListener) {#removeeventlistener}

Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | String | Указывает тип события удаляемого. |
| слушатель | IEventListener | Параметр указывает, что будет удалено. |

### См. также

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_1}

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

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
