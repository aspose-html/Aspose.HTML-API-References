---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML for Java API 参考"
description: "IEventTarget 方法。EventTarget 方法 addEventListener 设置一个函数，该函数将在指定事件传递给目标时被调用。"
type: docs

url: /zh/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

EventTarget 方法 addEventListener() 设置一个函数，该函数将在指定事件被发送到目标时被调用。

常见的目标有 Element、Document 和 Window，但目标可以是任何支持事件的对象（例如 XMLHttpRequest）。

```java
public void AddEventListener(String type, IEventListener listener)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | String | 表示要监听的事件类型的区分大小写的字符串。 |
| 监听器 | IEventListener | 接受用户实现的接口，其中包含事件发生时要调用的方法。 |

## 备注

如果在处理事件期间向 an 添加了一个，它不会被当前操作触发，但可能在事件流的后期阶段（例如冒泡阶段）被触发。如果在同一对象上使用相同参数注册了多个相同的 Event Listeners，重复的实例会被丢弃。它们不会导致被调用两次，并且由于已被丢弃，无需使用该方法将其移除。

### 另请参见

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

EventTarget 方法 addEventListener() 设置一个函数，该函数将在指定事件被发送到目标时被调用。

常见的目标有 Element、Document 和 Window，但目标可以是任何支持事件的对象（例如 XMLHttpRequest）。

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | String | 表示要监听的事件类型的区分大小写的字符串。 |
| 监听器 | IEventListener | 接受用户实现的接口，其中包含事件发生时要调用的方法。 |
| useCapture | Boolean | 如果为 true，useCapture 表示用户希望启动捕获。启动捕获后，所有指定类型的事件将在分派给任何位于树下的 Event Targets 之前，先分派给已注册的目标。向上冒泡通过树的事件将不会触发指定的使用捕获的目标。 |

## 备注

如果在处理事件期间向 an 添加了一个，它不会被当前操作触发，但可能在事件流的后期阶段（例如冒泡阶段）被触发。如果在同一对象上使用相同参数注册了多个相同的 Event Listeners，重复的实例会被丢弃。它们不会导致被调用两次，并且由于已被丢弃，无需使用该方法将其移除。

### 另请参见

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
