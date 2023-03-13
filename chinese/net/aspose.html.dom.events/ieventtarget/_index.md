---
title: Interface IEventTarget
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Events.IEventTarget 界面. 的EventTarget接口由支持 DOM 事件模型的实现中的所有节点实现 因此可以通过在 Node 接口的实例上使用特定于绑定的转换方法来获得此接口 该接口允许注册和删除事件侦听器一个EventTarget并向其发送事件IEventTarget.
type: docs
weight: 810
url: /zh/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

的[`EventTarget`](../../aspose.html.dom/eventtarget/)接口由支持 DOM 事件模型的实现中的所有节点实现。 因此，可以通过在 Node 接口的实例上使用特定于绑定的转换方法来获得此接口。 该接口允许注册和删除事件侦听器一个[`EventTarget`](../../aspose.html.dom/eventtarget/)并向其发送事件`IEventTarget`.

```csharp
public interface IEventTarget
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | 此方法允许将事件分派到实现事件模型中。 |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../ieventlistener/)从中删除[`EventTarget`](../../aspose.html.dom/eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../ieventlistener/)从中删除[`EventTarget`](../../aspose.html.dom/eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 部件 [Aspose.HTML](../../)


