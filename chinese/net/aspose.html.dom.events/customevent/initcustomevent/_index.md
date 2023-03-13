---
title: CustomEvent.InitCustomEvent
second_title: Aspose.HTML for .NET API 参考
description: CustomEvent 方法. /// 这个InitEvent方法用于初始化一个值Event通过创建IDocumentEvent接口.
type: docs
weight: 30
url: /zh/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// 这个[`InitEvent`](../../event/initevent/)方法用于初始化一个值[`Event`](../../event/)通过创建[`IDocumentEvent`](../../idocumentevent/)接口.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | String | 事件类型。 |
| bubbles | Boolean | 如果设置为`真的` [气泡]。 |
| cancelable | Boolean | 如果设置为`真的` [可取消]。 |
| detail | Object | 自定义数据。 |

### 评论

此方法只能在事件通过[`DispatchEvent`](../../ieventtarget/dispatchevent/)方法， 尽管在该阶段可能会在必要时调用多次。 如果多次调用，则最终调用优先。 如果从 Event 接口的子类调用，则仅修改 initEvent 方法中指定的值，所有其他属性保持不变.

### 也可以看看

* class [CustomEvent](../)
* 命名空间 [Aspose.Html.Dom.Events](../../customevent/)
* 部件 [Aspose.HTML](../../../)


