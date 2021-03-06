---
title: RemoveEventListener
second_title: Aspose.HTML for .NET API 参考
description: 此方法允许从事件目标中删除事件侦听器 如果IEventListeneraspose.html.dom.events/ieventlistener从EventTargetaspose.html.dom/eventtarget中删除而它正在处理一个事件它不会被当前操作触发 事件监听器在被移除后永远不能被调用
type: docs
weight: 40
url: /zh/net/aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../../eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 指定[`IEventListener`](../../../aspose.html.dom.events/ieventlistener)的事件类型被移除。 |
| handler | DOMEventHandler | [`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler)参数表示IEventListener被移除。 |
| useCapture | Boolean | 指定被移除的 EventListener 是否注册为捕获监听器。 如果一个监听器被注册了两次，一个有捕获，一个没有，每个都必须单独删除。 删除捕获侦听器不会影响同一侦听器的非捕获版本，反之亦然。 |

### 也可以看看

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler)
* class [EventTarget](../../eventtarget)
* 命名空间 [Aspose.Html.Dom](../../eventtarget)
* 部件 [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../../eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 指定[`IEventListener`](../../../aspose.html.dom.events/ieventlistener)的事件类型被移除。 |
| listener | IEventListener | [`IEventListener`](../../../aspose.html.dom.events/ieventlistener)参数表示IEventListener被移除。 |

### 也可以看看

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* 命名空间 [Aspose.Html.Dom](../../eventtarget)
* 部件 [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../../eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 指定[`IEventListener`](../../../aspose.html.dom.events/ieventlistener)的事件类型被移除。 |
| listener | IEventListener | [`IEventListener`](../../../aspose.html.dom.events/ieventlistener)参数表示IEventListener被移除。 |
| useCapture | Boolean | 指定被移除的 EventListener 是否注册为捕获监听器。 如果一个监听器被注册了两次，一个有捕获，一个没有，每个都必须单独删除。 删除捕获侦听器不会影响同一侦听器的非捕获版本，反之亦然。 |

### 也可以看看

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* 命名空间 [Aspose.Html.Dom](../../eventtarget)
* 部件 [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
