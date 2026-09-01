---
title: "SVGSVGElement.CreateEvent"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGSVGElement 方法。创建一个实现支持的类型的 Event。"
type: docs

url: /zh/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

创建一个实现支持的类型的 [`Event`](../../../com.aspose.html.dom.events/event/)。

```java
public Event CreateEvent(String eventType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| eventType | String | eventType 参数指定要创建的 [`Event`](../../../com.aspose.html.dom.events/event/) 接口的类型。如果实现支持指定的 [`Event`](../../../com.aspose.html.dom.events/event/) 接口，则此方法将返回一个新的[`Event`](../../../com.aspose.html.dom.events/event/)。如果要通过 [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) 方法分派该 [`Event`](../../../com.aspose.html.dom.events/event/)，则必须在创建后调用相应的[`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) 方法以初始化该 [`Event`](../../../com.aspose.html.dom.events/event/) 的值。 |

### 返回值

新创建的 [`Event`](../../../com.aspose.html.dom.events/event/)

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR：如果实现不支持请求的 [`Event`](../../../com.aspose.html.dom.events/event/) 接口类型，则会抛出此错误 |

### 另请参见

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
