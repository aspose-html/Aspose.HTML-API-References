---
title: "EventTarget.AddEventListener"
second_title: "Aspose.HTML for Java API 参考"
description: "EventTarget 方法。EventTarget 接口的 addEventListener 方法设置一个函数，当指定事件传递到目标时将被调用"
type: docs

url: /zh/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件传递到目标时被调用。

它通过向调用它的 EventTarget 上指定事件类型的事件监听器列表中添加一个函数或实现了 [EventListener](T:com.aspose.html.dom.events.IEventListener) 的对象来工作。如果该函数或对象已经在该目标的事件监听器列表中，则不会再次添加。

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | String | 用户正在注册的事件类型 |
| 处理程序 | DOMEventHandler | 接受一个在事件发生时被调用的函数。 |
| useCapture | Boolean | 如果为 true，useCapture 表示用户希望启动捕获。启动捕获后，所有指定类型的事件将在分派给任何位于树下的 Event Targets 之前，先分派给已注册的目标。向上冒泡通过树的事件将不会触发指定的使用捕获的目标。 |

## 备注

如果在处理事件期间向 an 添加了一个，它不会被当前操作触发，但可能在事件流的后期阶段（例如冒泡阶段）被触发。如果在同一对象上使用相同参数注册了多个相同的 Event Listeners，重复的实例会被丢弃。它们不会导致被调用两次，并且由于已被丢弃，无需使用该方法将其移除。

### 另请参见

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

[`EventTarget `](../) 接口的 addEventListener() 方法设置一个函数，当指定事件传递到目标时将被调用。

它通过向调用它的 EventTarget 上指定事件类型的事件监听器列表中添加一个函数或实现了 [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) 的对象来工作。如果该函数或对象已经在该目标的事件监听器列表中，则不会再次添加。

```java
public void AddEventListener(String type, IEventListener listener)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | String | 用户正在注册的事件类型 |
| 监听器 | IEventListener | 接受用户实现的接口，其中包含事件发生时要调用的方法。 |

## 备注

如果在处理事件期间向 an 添加了一个，它不会被当前操作触发，但可能在事件流的后期阶段（例如冒泡阶段）被触发。如果在同一对象上使用相同参数注册了多个相同的 Event Listeners，重复的实例会被丢弃。它们不会导致被调用两次，并且由于已被丢弃，无需使用该方法将其移除。

### 另请参见

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件传递到目标时被调用。

它通过向调用它的 EventTarget 上指定事件类型的事件监听器列表中添加一个函数或实现了 [EventListener](T:com.aspose.html.dom.events.IEventListener) 的对象来工作。如果该函数或对象已经在该目标的事件监听器列表中，则不会再次添加。

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | String | 用户正在注册的事件类型 |
| 监听器 | IEventListener | 接受用户实现的接口，其中包含事件发生时要调用的方法。 |
| useCapture | Boolean | 如果为 true，useCapture 表示用户希望启动捕获。启动捕获后，所有指定类型的事件将在分派给任何位于树下的 Event Targets 之前，先分派给已注册的目标。向上冒泡通过树的事件将不会触发指定的使用捕获的目标。 |

## 备注

如果在处理事件期间向 an 添加了一个，它不会被当前操作触发，但可能在事件流的后期阶段（例如冒泡阶段）被触发。如果在同一对象上使用相同参数注册了多个相同的 Event Listeners，重复的实例会被丢弃。它们不会导致被调用两次，并且由于已被丢弃，无需使用该方法将其移除。

### 另请参见

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
