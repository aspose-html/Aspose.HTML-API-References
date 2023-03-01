---
title: Document.CreateEvent
second_title: Aspose.HTML for .NET API 参考
description: Document 方法. 创建一个Event实现支持的类型
type: docs
weight: 880
url: /zh/net/aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

创建一个[`Event`](../../../aspose.html.dom.events/event/)实现支持的类型。

```csharp
public Event CreateEvent(string eventType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| eventType | String | eventType 参数指定的类型[`Event`](../../../aspose.html.dom.events/event/)要创建的接口.  如果[`Event`](../../../aspose.html.dom.events/event/)实现支持指定的接口此方法 will 返回一个新的[`Event`](../../../aspose.html.dom.events/event/)请求的接口类型。 如果[`Event`](../../../aspose.html.dom.events/event/)将通过[`DispatchEvent`](../../../aspose.html.dom.events/ieventtarget/dispatchevent/)适当的方法[`InitEvent`](../../../aspose.html.dom.events/event/initevent/) 方法必须在创建后调用以初始化[`Event`](../../../aspose.html.dom.events/event/) 值. |

### 返回值

新创建的[`Event`](../../../aspose.html.dom.events/event/)

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR：如果实现不支持的类型则引发[`Event`](../../../aspose.html.dom.events/event/)接口请求 |

### 也可以看看

* class [Event](../../../aspose.html.dom.events/event/)
* class [Document](../)
* 命名空间 [Aspose.Html.Dom](../../document/)
* 部件 [Aspose.HTML](../../../)


