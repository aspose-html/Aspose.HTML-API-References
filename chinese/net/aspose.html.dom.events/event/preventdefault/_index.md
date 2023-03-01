---
title: Event.PreventDefault
second_title: Aspose.HTML for .NET API 参考
description: Event 方法. 如果事件是可取消的则PreventDefault方法用于表示事件将被取消 表示作为事件结果通常由实现执行的任何默认操作都不会发生
type: docs
weight: 120
url: /zh/net/aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

如果事件是可取消的，则`PreventDefault`方法用于表示事件将被取消， 表示作为事件结果通常由实现执行的任何默认操作都不会发生。

```csharp
public void PreventDefault()
```

### 评论

如果在事件流的任何阶段，`PreventDefault`方法被调用事件被取消。 与事件关联的任何默认操作都不会发生。 为不可取消的事件调用此方法无效。 一次`PreventDefault`已被调用，它将在事件传播的其余部分保持有效。 此方法可在事件流的任何阶段使用。

### 也可以看看

* class [Event](../)
* 命名空间 [Aspose.Html.Dom.Events](../../event/)
* 部件 [Aspose.HTML](../../../)


