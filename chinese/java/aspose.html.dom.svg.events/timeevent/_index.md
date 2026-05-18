---
title: "TimeEvent 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.events.TimeEvent 类。TimeEvent 接口提供与时间事件相关的特定上下文信息。可能出现的事件类型包括 beginEvent、endEvent 和 repeatEvent。"
type: docs

url: /zh/java/com.aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

TimeEvent 接口提供与时间事件相关的特定上下文信息。可能发生的事件类型包括：beginEvent、endEvent 和 repeatEvent。

```java
public class TimeEvent : Event
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true，否则为 false。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) 用于指示事件是否可以阻止其默认行为。如果默认行为可以被阻止，则值为 true，否则为 false。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 用于指示当前正在处理的 [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/)，其 [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/) 正在被处理。这在捕获和冒泡阶段特别有用。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) 如果在 cancelable 属性为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [getDetail](../../com.aspose.html.dom.svg.events/timeevent/detail/) 指定关于 Event 的一些详细信息，取决于事件的类型。对于此事件类型，表示动画的重复次数。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 用于指示当前正在评估的事件流阶段。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted 属性必须返回其初始化时的值。创建事件时，该属性必须初始化为 false。 |
| [getTarget](../../com.aspose.html.dom.events/event/target/) 用于指示事件最初被分派到的 [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/)。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) 用于指定事件创建时的时间（相对于纪元的毫秒数）。由于某些系统可能不提供此信息，timeStamp 的值可能并非对所有事件都可用。若不可用，将返回 0。纪元时间的例子包括系统启动时间或 1970 年 1 月 1 日 UTC 0:0:0。 |
| [getType](../../com.aspose.html.dom.events/event/type/) 事件的名称（不区分大小写）。名称必须是有效的 XML 名称。 |
| [getView](../../com.aspose.html.dom.svg.events/timeevent/view/) view 属性标识生成该事件的 AbstractView [DOM2VIEWS]。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) 方法用于初始化通过 [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/) 接口创建的 [`Event`](../../com.aspose.html.dom.events/event/) 的值。 |
| [initTimeEvent](../../com.aspose.html.dom.svg.events/timeevent/inittimeevent/)(String, IAbstractView, long) | initTimeEvent 方法用于初始化通过 DocumentEvent 接口创建的 TimeEvent 的值。该方法只能在 TimeEvent 通过 dispatchEvent 方法分派之前调用，尽管在该阶段如有必要可以多次调用。如果多次调用，则以最后一次调用为准。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | 如果事件是可取消的，[`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) 方法用于表示该事件应被取消，这意味着实现通常会因该事件而执行的任何默认操作都不会发生。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | 调用此方法可阻止事件到达在当前监听器之后注册的任何事件监听器，并且在树状分派时也阻止事件到达任何其他对象。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) 方法用于阻止事件在事件流中的进一步传播。 |

### 另请参阅

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
