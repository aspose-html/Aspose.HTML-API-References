---
title: CreateEvent
second_title: Aspose.HTML for .NET API 参考
description: 创建实现支持的类型的Eventaspose.html.dom.events/event
type: docs
weight: 110
url: /zh/net/aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

创建实现支持的类型的[`Event`](../../../aspose.html.dom.events/event)。

```csharp
public Event CreateEvent(string eventType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| eventType | String | eventType 参数指定Event接口。  如果实现支持指定的[`Event`](../../../aspose.html.dom.events/event)接口此方法将返回请求的接口类型的新 [`Event`](../../../aspose.html.dom.events/event)。 如果[`Event`](../../../aspose.html.dom.events/event)将通过Event)方法适当的 [`InitEvent`](../../../aspose.html.dom.events/event/initevent)方法必须在创建后调用才能初始化[`Event`](../../../aspose.html.dom.events/event)的值。 |

### 返回值

新创建的[`Event`](../../../aspose.html.dom.events/event)

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception) | NOT_SUPPORTED_ERR:如果实现不支持[`Event`](../../../aspose.html.dom.events/event)接口请求的类型，则引发 |

### 也可以看看

* class [Event](../../../aspose.html.dom.events/event)
* class [SVGSVGElement](../../svgsvgelement)
* 命名空间 [Aspose.Html.Dom.Svg](../../svgsvgelement)
* 部件 [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
