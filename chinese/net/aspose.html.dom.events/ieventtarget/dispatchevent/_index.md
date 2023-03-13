---
title: IEventTarget.DispatchEvent
second_title: Aspose.HTML for .NET API 参考
description: IEventTarget 方法. 此方法允许将事件分派到实现事件模型中
type: docs
weight: 20
url: /zh/net/aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

此方法允许将事件分派到实现事件模型中。

```csharp
public bool DispatchEvent(Event @event)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| event | Event | 指定要在处理事件时使用的事件类型、行为和上下文信息。 |

### 返回值

的返回值[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/)指示是否有任何处理事件的侦听器调用[`PreventDefault`](../../event/preventdefault/). 如果[`PreventDefault`](../../event/preventdefault/)被称为值为 false，否则值为 true.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) |  |

### 评论

以这种方式派发的事件将具有与实现直接派发的事件相同的捕获和冒泡行为。 事件的目标是[`EventTarget`](../../../aspose.html.dom/eventtarget/)在哪个[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/)被称为.

### 也可以看看

* class [Event](../../event/)
* interface [IEventTarget](../)
* 命名空间 [Aspose.Html.Dom.Events](../../ieventtarget/)
* 部件 [Aspose.HTML](../../../)


