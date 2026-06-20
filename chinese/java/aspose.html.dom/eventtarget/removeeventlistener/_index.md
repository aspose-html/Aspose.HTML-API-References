---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.HTML for Java API 参考"
description: "EventTarget 方法。此方法允许从事件目标中移除事件监听器。如果在处理事件期间将其移除，则当前操作不会触发它。事件监听器在被移除后永远不会被调用"
type: docs

url: /zh/java/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | String | 指定被移除的事件类型。 |
| 处理程序 | DOMEventHandler | 该参数指示要被移除的对象。 |
| useCapture | Boolean | 指定被移除的 EventListener 是否已注册为捕获监听器。如果同一个监听器被注册了两次，一次使用捕获一次不使用，则必须分别移除。移除捕获监听器不会影响同一监听器的非捕获版本，反之亦然。 |

### 另请参见

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | String | 指定被移除的事件类型。 |
| 监听器 | IEventListener | 该参数指示要被移除的对象。 |

### 另请参见

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | String | 指定被移除的事件类型。 |
| 监听器 | IEventListener | 该参数指示要被移除的对象。 |
| useCapture | Boolean | 指定被移除的 EventListener 是否已注册为捕获监听器。如果同一个监听器被注册了两次，一次使用捕获一次不使用，则必须分别移除。移除捕获监听器不会影响同一监听器的非捕获版本，反之亦然。 |

### 另请参见

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
