---
title: "事件 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.events.Event 类。它用于向处理事件的处理程序提供关于事件的上下文信息"
type: docs

url: /zh/java/com.aspose.html.dom.events/event/
---
## Event class

用于向处理该事件的处理程序提供有关事件的上下文信息。

```java
public class Event : DOMObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Event](event/#constructor)(String) | 初始化 `Event` 类的新实例。 |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## 属性

| 名称 | 描述 |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true，否则为 false。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) 用于指示事件是否可以阻止其默认行为。如果默认行为可以被阻止，则值为 true，否则为 false。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 用于指示当前正在处理的 [`IEventTarget`](../ieventtarget/) 及其 [`IEventListener`](../ieventlistener/)。这在捕获和冒泡阶段特别有用。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) 如果在 cancelable 属性为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 用于指示当前正在评估的事件流阶段。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted 属性必须返回其初始化时的值。创建事件时，该属性必须初始化为 false。 |
| [getTarget](../../com.aspose.html.dom.events/event/target/) 用于指示事件最初分派到的 [`IEventTarget`](../ieventtarget/)。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) 用于指定事件创建时的时间（相对于纪元的毫秒数）。由于某些系统可能不提供此信息，timeStamp 的值可能并非对所有事件都可用。若不可用，将返回 0。纪元时间的例子包括系统启动时间或 1970 年 1 月 1 日 UTC 0:0:0。 |
| [getType](../../com.aspose.html.dom.events/event/type/) 事件的名称（不区分大小写）。名称必须是有效的 XML 名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | 使用 [`InitEvent`](./initevent/) 方法来初始化通过 [`IDocumentEvent`](../idocumentevent/) 接口创建的 `Event` 的值。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | 如果事件是可取消的，使用 [`PreventDefault`](./preventdefault/) 方法表示该事件应被取消，这意味着实现通常会因该事件而执行的任何默认操作将不会发生。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | 调用此方法可阻止事件到达在当前监听器之后注册的任何事件监听器，并且在树状分派时也阻止事件到达任何其他对象。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | 使用 [`StopPropagation`](./stoppropagation/) 方法阻止事件在事件流中的进一步传播。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | 当前事件阶段是捕获阶段。 |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | 当前事件阶段是冒泡阶段。 |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | 事件当前正在目标 [`IEventTarget`](../ieventtarget/) 处评估。 |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | 未当前分派的事件位于此阶段。 |

## 备注

实现该接口的对象通常作为第一个参数传递给事件处理程序。通过从中派生额外的接口并包含直接与其伴随的事件类型相关的信息，可向事件处理程序传递更具体的上下文信息。这些派生接口也由传递给事件监听器的对象实现。

### 另请参阅

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
