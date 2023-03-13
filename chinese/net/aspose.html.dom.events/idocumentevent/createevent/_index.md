---
title: IDocumentEvent.CreateEvent
second_title: Aspose.HTML for .NET API 参考
description: IDocumentEvent 方法. 创建一个Event实现支持的类型
type: docs
weight: 10
url: /zh/net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

创建一个[`Event`](../../event/)实现支持的类型。

```csharp
public Event CreateEvent(string eventType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| eventType | String | eventType 参数指定的类型[`Event`](../../event/)要创建的接口.  如果[`Event`](../../event/)实现支持指定的接口此方法将返回 new [`Event`](../../event/)请求的接口类型。 如果[`Event`](../../event/)将通过[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/)方法 appropriate [`InitEvent`](../../event/initevent/)方法必须在创建后调用以初始化[`Event`](../../event/) 值. |

### 返回值

新创建的[`Event`](../../event/)

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR：如果实现不支持类型则引发[`Event`](../../event/)接口请求 |

### 也可以看看

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* 命名空间 [Aspose.Html.Dom.Events](../../idocumentevent/)
* 部件 [Aspose.HTML](../../../)


