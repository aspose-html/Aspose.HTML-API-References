---
title: "InputEvent 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.events.InputEvent 类。输入事件在 DOM 更新时作为通知发送。"
type: docs

url: /zh/java/com.aspose.html.dom.events/inputevent/
---
## InputEvent class

当 DOM 被更新时，输入事件会作为通知发送。

```java
public class InputEvent : UIEvent
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [InputEvent](inputevent/#constructor)(String) | 初始化 `InputEvent` 类的新实例。 |
| [InputEvent](inputevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## 属性

| 名称 | 描述 |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true，否则为 false。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) 用于指示事件是否可以阻止其默认行为。如果默认行为可以被阻止，则值为 true，否则为 false。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 用于指示当前正在处理的 [`IEventTarget`](../ieventtarget/) 及其 [`IEventListener`](../ieventlistener/)。这在捕获和冒泡阶段特别有用。 |
| [getData](../../com.aspose.html.dom.events/inputevent/data/) 数据保存由输入法生成的字符值。它可能是单个 Unicode 字符或非空的 Unicode 字符序列 [Unicode]。字符应按照 Unicode 规范化形式 NFC（在 [UAX15] 中定义）进行规范化。此属性可能包含空字符串。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) 如果在 cancelable 属性值为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) 指定有关 Event 的一些详细信息，取决于事件的类型。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 用于指示当前正在评估的事件流阶段。 |
| [getIsComposing](../../com.aspose.html.dom.events/inputevent/iscomposing/) 如果输入事件是组成会话的一部分，则为 true，即在 compositionstart 事件之后、对应的 compositionend 事件之前。此属性的未初始化值必须为 false。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) 该 isTrusted 属性必须返回其初始化时的值。当创建事件时，该属性必须初始化为 false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) 用于指示事件最初分派到的 [`IEventTarget`](../ieventtarget/)。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) 用于指定事件创建时的时间（相对于纪元的毫秒数）。由于某些系统可能不提供此信息，timeStamp 的值可能并非对所有事件都可用。若不可用，将返回 0。纪元时间的示例包括系统启动时间或 1970 年 1 月 1 日 00:00:00 UTC。 |
| [getType](../../com.aspose.html.dom.events/event/type/) 该事件的名称（不区分大小写）。名称必须是 XML 名称。 |
| [getView](../../com.aspose.html.dom.events/uievent/view/) view 属性标识生成事件的 Window。该属性的未初始化值必须为 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | 该 [`InitEvent`](../event/initevent/) 方法用于初始化通过 [`IDocumentEvent`](../idocumentevent/) 接口创建的 [`Event`](../event/) 的值。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | 如果事件是可取消的，则使用 [`PreventDefault`](../event/preventdefault/) 方法表示该事件将被取消，即实现通常因该事件而执行的任何默认操作都不会发生。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | 调用此方法可阻止事件到达在当前监听器之后注册的任何事件监听器，并且在树状分派时也阻止事件到达其他对象。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | 该 [`StopPropagation`](../event/stoppropagation/) 方法用于阻止事件在事件流中的进一步传播。 |

### 另请参见

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
