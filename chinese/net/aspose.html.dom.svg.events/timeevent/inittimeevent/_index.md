---
title: TimeEvent.InitTimeEvent
second_title: Aspose.HTML for .NET API 参考
description: TimeEvent 方法. initTimeEvent 方法用于初始化通过 DocumentEvent 接口创建的 TimeEvent 的值只能在通过 dispatchEvent 方法分派 TimeEvent 之前调用此方法但如有必要可能会在该阶段多次调用它如果多次调用最后一次调用优先
type: docs
weight: 30
url: /zh/net/aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

initTimeEvent 方法用于初始化通过 DocumentEvent 接口创建的 TimeEvent 的值。只能在通过 dispatchEvent 方法分派 TimeEvent 之前调用此方法，但如有必要，可能会在该阶段多次调用它。如果多次调用，最后一次调用优先。

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| typeArg | String | 指定事件类型。 |
| viewArg | IAbstractView | 指定事件的 AbstractView。 |
| detailArg | Int64 | 指定事件的详细信息。 |

### 也可以看看

* interface [IAbstractView](../../../aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* 命名空间 [Aspose.Html.Dom.Svg.Events](../../timeevent/)
* 部件 [Aspose.HTML](../../../)


