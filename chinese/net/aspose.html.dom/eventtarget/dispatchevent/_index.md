---
title: EventTarget.DispatchEvent
second_title: Aspose.HTML for .NET API 参考
description: EventTarget 方法. 此方法允许将事件分派到实现事件模型中
type: docs
weight: 20
url: /zh/net/aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

此方法允许将事件分派到实现事件模型中。

```csharp
public bool DispatchEvent(Event @event)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| event | Event | 指定要在处理事件时使用的事件类型、行为和上下文信息。 |

### 返回值

的返回值`DispatchEvent`指示是否有任何处理事件的侦听器调用[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/). 如果[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/)被称为值为 false，否则值为 true.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../domexception/) |  |

### 评论

以这种方式派发的事件将具有与实现直接派发的事件相同的捕获和冒泡行为。 事件的目标是[`EventTarget`](../)在哪个`DispatchEvent`被称为.

### 也可以看看

* class [Event](../../../aspose.html.dom.events/event/)
* class [EventTarget](../)
* 命名空间 [Aspose.Html.Dom](../../eventtarget/)
* 部件 [Aspose.HTML](../../../)


