---
title: EventTarget.AddEventListener
second_title: Aspose.HTML for .NET API 参考
description: EventTarget 方法. 此方法允许在事件目标上注册事件侦听器
type: docs
weight: 10
url: /zh/net/aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(string, DOMEventHandler, bool) {#addeventlistener}

此方法允许在事件目标上注册事件侦听器。

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 用户注册的事件类型 |
| handler | DOMEventHandler | 需要一个[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/)事件发生时被调用。 |
| useCapture | Boolean | 如果为true，useCapture表示用户希望发起捕获。 发起捕获后，指定类型的所有事件将被派发到registered [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) 在被分派到树中它们下面的任何事件目标之前。 通过树向上冒泡的事件不会触发[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/)指定使用捕获。 |

### 评论

如果一个[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/)被添加到一个[`EventTarget`](../)当它正在处理事件时，它不会被当前操作触发 ，但可能会在事件流的后期触发，例如冒泡阶段。

如果多个相同的事件监听器注册在同一个[`EventTarget`](../)使用相同的参数，重复的实例将被丢弃。 它们不会导致[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/)被调用两次，因为它们被丢弃，所以不需要用 the 删除它们[`RemoveEventListener`](../removeeventlistener/) 方法.

### 也可以看看

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* 命名空间 [Aspose.Html.Dom](../../eventtarget/)
* 部件 [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener) {#addeventlistener_1}

此方法允许在事件目标上注册事件侦听器。

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 用户注册的事件类型 |
| listener | IEventListener | 采用用户实现的接口，其中包含事件发生时要调用的方法。 |

### 评论

如果一个[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/)被添加到一个[`EventTarget`](../)当它正在处理事件时，它不会被当前操作触发 ，但可能会在事件流的后期触发，例如冒泡阶段。

如果多个相同的事件监听器注册在同一个[`EventTarget`](../)使用相同的参数，重复的实例将被丢弃。 它们不会导致[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/)被调用两次，因为它们被丢弃，所以不需要用 the 删除它们[`RemoveEventListener`](../removeeventlistener/) 方法.

### 也可以看看

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* 命名空间 [Aspose.Html.Dom](../../eventtarget/)
* 部件 [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_2}

此方法允许在事件目标上注册事件侦听器。

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 用户注册的事件类型 |
| listener | IEventListener | 采用用户实现的接口，其中包含事件发生时要调用的方法。 |
| useCapture | Boolean | 如果为true，useCapture表示用户希望发起捕获。 发起捕获后，指定类型的所有事件将被派发到registered [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) 在被分派到树中它们下面的任何事件目标之前。 通过树向上冒泡的事件不会触发[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/)指定使用捕获。 |

### 评论

如果一个[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/)被添加到一个[`EventTarget`](../)当它正在处理事件时，它不会被当前操作触发 ，但可能会在事件流的后期触发，例如冒泡阶段。

如果多个相同的事件监听器注册在同一个[`EventTarget`](../)使用相同的参数，重复的实例将被丢弃。 它们不会导致[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/)被调用两次，因为它们被丢弃，所以不需要用 the 删除它们[`RemoveEventListener`](../removeeventlistener/) 方法.

### 也可以看看

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* 命名空间 [Aspose.Html.Dom](../../eventtarget/)
* 部件 [Aspose.HTML](../../../)


