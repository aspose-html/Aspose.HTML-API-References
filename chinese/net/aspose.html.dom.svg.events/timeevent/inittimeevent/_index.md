---
title: InitTimeEvent
second_title: Aspose.HTML for .NET API 参考
description: initTimeEvent 方法用于初始化通过 DocumentEvent 接口创建的 TimeEvent 的值此方法只能在通过 dispatchEvent 方法分派 TimeEvent 之前调用但如果需要可以在该阶段多次调用此方法如果多次调用最终调用优先
type: docs
weight: 30
url: /zh/net/aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

initTimeEvent 方法用于初始化通过 DocumentEvent 接口创建的 TimeEvent 的值。此方法只能在通过 dispatchEvent 方法分派 TimeEvent 之前调用，但如果需要，可以在该阶段多次调用此方法。如果多次调用，最终调用优先。

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| typeArg | String | 指定事件类型。 |
| viewArg | IAbstractView | 指定事件的 AbstractView。 |
| detailArg | Int64 | 指定事件的详细信息。 |

### 也可以看看

* interface [IAbstractView](../../../aspose.html.dom.views/iabstractview)
* class [TimeEvent](../../timeevent)
* 命名空间 [Aspose.Html.Dom.Svg.Events](../../timeevent)
* 部件 [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->