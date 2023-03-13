---
title: Class EventTarget
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.EventTarget 班级. 的EventTarget接口由支持 DOM 事件模型的实现中的所有节点实现 因此可以通过在 Node 接口的实例上使用特定于绑定的转换方法来获得此接口 该接口允许注册和删除事件侦听器一个EventTarget并向其发送事件IEventTarget.
type: docs
weight: 720
url: /zh/net/aspose.html.dom/eventtarget/
---
## EventTarget class

的`EventTarget`接口由支持 DOM 事件模型的实现中的所有节点实现。 因此，可以通过在 Node 接口的实例上使用特定于绑定的转换方法来获得此接口。 该接口允许注册和删除事件侦听器一个`EventTarget`并向其发送事件[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/).

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(string, DOMEventHandler, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(string, IEventListener, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | 此方法允许将事件分派到实现事件模型中。 |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | 执行与释放、释放或重置非托管资源相关的应用程序定义的任务。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除`EventTarget`当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(string, DOMEventHandler, bool) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除`EventTarget`当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(string, IEventListener, bool) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除`EventTarget`当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |

### 也可以看看

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* 命名空间 [Aspose.Html.Dom](../../aspose.html.dom/)
* 部件 [Aspose.HTML](../../)


