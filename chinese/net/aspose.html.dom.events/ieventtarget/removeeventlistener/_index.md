---
title: IEventTarget.RemoveEventListener
second_title: Aspose.HTML for .NET API 参考
description: IEventTarget 方法. 此方法允许从事件目标中删除事件侦听器 如果一个IEventListener从中删除EventTarget当它正在处理一个事件时它不会被当前的动作触发 事件监听器在被移除后永远不会被调用
type: docs
weight: 30
url: /zh/net/aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../ieventlistener/)从中删除[`EventTarget`](../../../aspose.html.dom/eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 指定事件类型[`IEventListener`](../../ieventlistener/)被删除。 |
| listener | IEventListener | 这[`IEventListener`](../../ieventlistener/)参数表示[`IEventListener`](../../ieventlistener/)即将被删除。 |

### 也可以看看

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* 命名空间 [Aspose.Html.Dom.Events](../../ieventtarget/)
* 部件 [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../ieventlistener/)从中删除[`EventTarget`](../../../aspose.html.dom/eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 指定事件类型[`IEventListener`](../../ieventlistener/)被删除。 |
| listener | IEventListener | 这[`IEventListener`](../../ieventlistener/)参数表示[`IEventListener`](../../ieventlistener/)即将被删除。 |
| useCapture | Boolean | 指定被删除的 EventListener 是否注册为捕获侦听器。 如果一个侦听器被注册了两次，一个有捕获，一个没有，每个都必须单独删除。 捕获侦听器的删除不会影响非捕获版本同一个听众，反之亦然。 |

### 也可以看看

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* 命名空间 [Aspose.Html.Dom.Events](../../ieventtarget/)
* 部件 [Aspose.HTML](../../../)


