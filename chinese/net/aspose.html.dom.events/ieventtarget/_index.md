---
title: IEventTarget
second_title: Aspose.HTML for .NET API 参考
description: EventTarget../aspose.html.dom/eventtarget接口由支持 DOM 事件模型的实现中的所有节点实现 因此可以通过在 Node 接口的实例上使用特定于绑定的强制转换方法来获得此接口 该接口允许在EventTarget../aspose.html.dom/eventtarget上注册和删除事件侦听器并将事件分派到IEventTarget
type: docs
weight: 920
url: /zh/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

[`EventTarget`](../../aspose.html.dom/eventtarget)接口由支持 DOM 事件模型的实现中的所有节点实现。 因此，可以通过在 Node 接口的实例上使用特定于绑定的强制转换方法来获得此接口。 该接口允许在[`EventTarget`](../../aspose.html.dom/eventtarget)上注册和删除事件侦听器，并将事件分派到IEventTarget。

```csharp
public interface IEventTarget
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener#addeventlistener)(string, IEventListener) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener#addeventlistener_1)(string, IEventListener, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent)(Event) | 此方法允许将事件分派到实现事件模型中。 |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener#removeeventlistener)(string, IEventListener) | 此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../ieventlistener)从[`EventTarget`](../../aspose.html.dom/eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。 |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener#removeeventlistener_1)(string, IEventListener, bool) | 此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../ieventlistener)从[`EventTarget`](../../aspose.html.dom/eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* 部件 [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
